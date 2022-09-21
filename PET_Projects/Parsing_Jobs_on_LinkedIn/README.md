# Parsing Jobs on LinkedIn

![image](https://user-images.githubusercontent.com/93816292/191527798-bba9dbd7-1743-4ca6-8b26-a85de31ba3bc.png)
[link on tableau.com](https://public.tableau.com/app/profile/igor.shirokov/viz/LinkedInAnalysisofDataScientistsVacancies/LinkedInAnalysisofDataScientistsVacancies)


## Project Description

In order to compile a dashboard, you need to gather Data Scientist vacancies data from LinkedIn.

## Tasks

1. Parse LinkedIn jobs using BS 4 and Selenium by creating the following features:

- job title;
- city;
- country;
- employment type (online, hybrid, on-site);
- company;
- company size (number of employees);
- scope of the company;
- required hard skills;
- date of publication of the vacancy;
- number of job applicants.

2.Prepare data for visualization:

- dataframe filtering leaving only vacancies for Data Dcientists;
- removal of duplicates;
- removal of unnecessary attributes (features).

## Libraries used

- pandas
- numpy
- seaborn
- re
- dotenv
- matplotlib
- requests
- webdriver_manager
- bs4
- selenium
