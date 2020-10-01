# Creating-holidays-datasets-using-nager

In this project I used [Nager.Date API](https://date.nager.at/Api) to create datasets of holidays and long weekends.

## Data


The data was retrieved using GET requests to https://date.nager.at/Api/v2/PublicHolidays/{year}/{countrycode} and https://date.nager.at/Api/v2/LongWeekend/{year}/{countrycode} and then transformed into `csv` files:
* world_holidays_2019.csv
* world_long_weekends_2019.csv

## Project Goal


The goal of the project was to prepare two datasets of world holidays and long weekends for a futher analysis.

## Installation 


You can install all the necessary libraries to run the project by running:

```conda create --name <env_name> --file requirements.txt```

if using `conda`

or

```pip install -r requirements.txt```

if using `pip`.

