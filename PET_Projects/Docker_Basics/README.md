# Docker for Data Science

## Project Description

The simple project based on [Gleb Mikhailov awesome education videos](https://www.youtube.com/playlist?list=PLQJ7ptkRY-xbR0ka2TUxJkXna40XWu92m)

## Tasks

- Compose two docker containers.
- Connect to the postgres database and run test queries.

## Algorithm

* Get jupyter.
```
docker run -v $pwd/notebooks:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:9e63909e0317
```

* Check what's inside the container.
```
docker exec -it 824142393a85 bash
```

* Create Dockerfile to build container with psycopg2-binary.
```
FROM jupyter/scipy-notebook:9e63909e0317
RUN pip install psycopg2-binary
```

* Create Docker-compose.yml to compose postgres and jupiter app.
```
version: "4"

services:
  postgres:
      image: postgres:latest
      restart: always
      environment:
        - POSTGRES_USER=postgres
        - POSTGRES_PASSWORD=postgres
      volumes:
        - ./postgree:/var/lib/postgresql/data
      ports:
        - '5432:5432'
        
  jupiter_app:
    build:
      context: .
      dockerfile: ./Dockerfile
    volumes:
      - ./notebooks:/home/jovyan/
    ports:
      - '8888:8888'
    links:
      - postgres
```

* Run docker-compose in detached mode.
```
docker-compose up -d --build
```


## Libraries used

- sqlalchemy
- psycopg2