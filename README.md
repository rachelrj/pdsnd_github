# Bikeshare Data Analyzer

The bikeshare data analyzer takes csv inputs, analyzes those, and outputs readable and understandable facts to the user.

## Date Created

The original project that this project was forked from was created years ago. This version was created July 30, 2024.

## Description

The user inputs the city, month, and day for which they want the data from the csv file analyzed. The program outputs:

- Statistics on the most frequent times of travel.
- Statistics on the most popular stations and trip.
- Statistics on the total and average trip duration.
- Statistics on bikeshare users.

## Installation Instructions

Install dependencies

```
pip install -r requirements.txt
```

Run the project

```
python3 bikeshare_2.py
```

or

```
python bikeshare_2.py
```

Depending on your version of python installed.

## Files used

The project analyzes csv files that are located in the root of the project.

Columns are Start Time,End Time,Trip Duration,Start Station,End Station,User Type,Gender,Birth Year

One data piece per line

CSV files should be named by city. If city contains space, replace with underscore.

## Credits

This is a forked project from Udacity's starter repository. See fork below project link. The libraries used include:

- time
- pandas
- numpy
- os
