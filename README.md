# Exploratory Data Analysis Project

## Marketing Campaign Predictions Using the MTA Turnstiles Dataset

By: Leah Nagy

### Contents:

1.  [Slide Presentation](https://github.com/leahnagy/eda_mta/blob/main/MTA%20Traffic%20Exploratory%20Data%20Analysis.pdf)
2.  [Python Scripts](https://github.com/leahnagy/eda_mta/blob/main/code_mta_eda.ipynb)

## Project Description

Namaste Home, a leading yoga & meditation streaming app, is launching Namaste Campus -- a dedicated app tailored for college students. As part of their marketing strategy, they aim to conduct live demonstrations of the app at bustling MTA subway stations near NYC college campuses in the first week of September. This project's primary objective is to identify the optimal days, times, and stations for hosting these demonstrations to maximize engagement and exposure among the target demographic.

## Project Design

As part of the Metis Data Science Bootcamp curriculum, this project leverages the MTA Turnstile Dataset -- a rich repository of entry and exit counts for each turnstile in every NYC station. Analyzing patterns in this traffic data will empower the marketing team of Namaste Campus with data-driven insights on the most advantageous day, time, and station for their promotional activities.

## Data Collection and Processing

The MTA dataset spanning several years was scoped to focus on the first week of September. However, 2020 data was excluded due to the widespread shift to remote learning amid the pandemic. The analysis was conducted using data from 2018, 2019, and 2021, specifically from ten stations in proximity to a college or university. Further refining our data scope, we focused on afternoon and evening entries, anticipating these times to correspond with students leaving campus and being less hurried than their morning commutes.

## Methodology

The data analysis process involved the following steps:

1.  Identify college locations and nearby MTA stations
2.  Clean and preprocess the data for analysis
3.  Identify the top three stations with the highest afternoon/evening entries
4.  Determine the busiest days of the week based on trends from past years

## Tools Utilized

-   SQLite for data import and database creation
-   NumPy and Pandas for data manipulation and analysis
-   Matplotlib for data visualization
-   Tableau for geographical representation

## Dissemination

Findings from this project, along with relevant visuals, are shared on my [**Medium blog**](https://medium.com/@leahnagy) and on [**GitHub**](https://github.com/leahnagy). The Slide Presentation included in the Contents above provides a succinct overview of the project's key insights.
