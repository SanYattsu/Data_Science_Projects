# PostgreSQL Investments | Database Creation & Extraction


## Content

This diverse dataset contains information about the startup ecosystem: organizations, individuals, company news, funding rounds, acquisitions, and IPOs. More information about the individual data variables can be found on the Crunchabse Data website (under the API Entities Types section). The information is available up to December 2013. [Kaggle Dataset](https://www.kaggle.com/datasets/justinas/startup-investments)


## Goals

- Create a database from existing .csv tables in ElephantSQL.
- Upload the necessary data in accordance with the requests.


## Data

CSV tables:

- objects
- acquisitions
- degrees
- funding_rounds
- funds
- investments
- ipos
- milestones
- offices
- people
- relationships

## Libraries used

- pandas
- glob
- psycopg2
- sqlalchemy
- sql