# Tariff Determination for a Telecom Company

## Project Description
Determination of the most profitable tariff of the federal mobile operator, to adjust the advertising budget of the commercial department.

## Data

### Table users (information about users):
* user_id - unique user ID
* first_name - username
* last_name - last name of the user
* age — user's age (years)
* reg_date — tariff connection date (day, month, year)
* churn_date — date when the tariff was discontinued (if the value is omitted, then the tariff was still valid at the time of data upload)
* city — user's city of residence
* tarif — tariff plan name

### The calls table (information about calls):
* id - unique call number
* call_date — call date
* duration — call duration in minutes
* user_id — identifier of the user who made the call

### Messages table (message information):
* id - unique message number
* message_date — message date
* user_id - ID of the user who sent the message

### Internet table (information about internet sessions):
* id — unique session number
* mb_used - the amount of Internet traffic spent per session (in megabytes)
* session_date — internet session date
* user_id - user ID

### Tariffs table (tariff information):
* tariff_name — tariff name
* rub_monthly_fee — monthly subscription fee in rubles
* minutes_included - the number of minutes of conversation per month included in the subscription fee
* messages_included - number of messages per month included in the subscription fee
* mb_per_month_included - the amount of Internet traffic included in the subscription fee (in megabytes)
* rub_per_minute - the cost of a minute of conversation in excess of the tariff package
* rub_per_message - the cost of sending a message in excess of the tariff package
* rub_per_gb - the cost of an additional gigabyte of Internet traffic in excess of the tariff package (1 gigabyte = 1024 megabytes)

## Task
Conduct an analysis of customer behavior and conclude which tariff is better.

## Libraries used
- pandas
- numpy
- seaborn
- matplotlib
- re
- scipy
