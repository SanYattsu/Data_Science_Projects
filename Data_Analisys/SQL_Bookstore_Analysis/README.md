# Overview analysis of a bookstore | SQL

## Task

Analyze the database.

## Data

**Table books**

Contains information about books:

- book_id — book identifier;
- author_id — author identifier;
- title — title of the book;
- num_pages - number of pages;
- publication_date - publication date of the book;
- publisher_id - publisher identifier.

**The authors table**

Contains information about the authors:

- author_id — author identifier;
- author is the name of the author.

**Table publishers**

Contains information about publishers:

- publisher_id — publisher identifier;
- publisher — publisher name;

**Table ratings**

Contains data about user ratings of books:

- rating_id — rating identifier;
- book_id — book identifier;
- username - the name of the user who left the rating;
- rating - rating of the book.

**Table reviews**

Contains data about user reviews of books:

- review_id — review identifier;
- book_id — book identifier;
- username - the name of the user who wrote the review;
- text — review text.

## Libraries used

- pandas
- numpy
- seaborn
- matplotlib
- dotenv
- sqlalchemy
