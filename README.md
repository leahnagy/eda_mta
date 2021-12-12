# eda_mta
MTA Turnstile Project 

# Exploratory Data Analysis Project

## Marketing Campaign Predictions Using the MTA Turnstiles Dataset
By: Leah Nagy

## Abstract
Namaste Home, a yoga & meditation streaming app, is launching a new app just for college students – Namaste Campus. They would like to display an in-person demonstration of the app in busy New York City MTA subway stations near college campuses during the first week of September. The goal of this project was to find the best days/times and stations to host the demonstrations. After finding stations close to major colleges and universities, I analyzed the data to determine the best options for the campaign team and displayed those results in the PDF slide presentation.

## Design
This project is a part of the Metis Data Science Bootcamp. It utilizes the MTA Turnstile Dataset found on the MTA website which records the number of entries and exits for each turnstile in every station across New York City. Understanding the amount of traffic in each station at different times will help Namaste Campus's marketing team determine the ideal day, time and location for the campaign to reach the most college students.

## Data
The dataset included the target week, the first week of September, over several years to reveal any trends. I chose to ignore the data from 2020 since many colleges moved to distance learning during the pandemic. I used the data from 2018, 2019, and 2021 and included only the data from the ten stations near a college or university.  I further narrowed the data to include only the afternoon and evening entries, as this is the most common time for students to leave campus and they will not be rushing to get to their first class.  

## Algorithms

1.	Research college and MTA station locations
2.	Clean and prepare the data for analysis
3.	Find the top three stations with the most afternoon/evening entries
4.	Determine the best days of the week looking at previous years

## Tools
* SQLite to import data and create a database
* NumPy and Pandas for data manipulation
* Matplotlib for plotting
* Tableau for mapping

## Communication
In addition to the slides and visuals presented, this project will be embedded on my personal blog on Medium and on GitHub.
