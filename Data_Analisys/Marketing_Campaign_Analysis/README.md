# Marketing Campaign Analysis

## Task

Help marketers optimize marketing costs by analyzing the available data from Yandex.Afisha from June 2017 to the end of May 2018.

## Data

Visits table (server log with information about site visits):

- Uid - unique user ID
- Device — user device category
- Start Ts - date and time of the session start
- End Ts — date and time of the end of the session
- Source Id - identifier of the advertising source from which the user came

Table orders (information about orders):

- Uid - unique id of the user who made the order
- Buy Ts - date and time of order
- Revenue — Yandex.Afisha's revenue from this order

Costs table (information about marketing costs):

- source_id - ad source ID
- dt - date
- costs — costs for this advertising source on this day

## Libraries used

- pandas
- numpy
- seaborn
- matplotlib
- dotenv
