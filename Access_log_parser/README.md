# Access log parser

## Project Goals
* Download access.log.
* Generate a CSV file with a list of unique IP addresses from get requests. For each of them, the number of successful get-requests from this address, and the number of all other get-requests should be indicated.
* Display the list of TOP30 IP addresses with the highest number of successful get requests.

## Libraries used
- pandas
- numpy
- wget
- re