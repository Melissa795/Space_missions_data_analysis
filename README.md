# Space Missions Dataset Analysis

## Overview
This project aims to analyze the space missions dataset, exploring various aspects such as launch trends over time, mission outcomes, popular rocket types, and key launch sites. The dataset encompasses space mission records from 1957 to 2022. The dataset was sourced from [Maven Analytics](https://www.mavenanalytics.io/data-playground?page=6&pageSize=5).

## Dataset Fields

| Field          | Description                                                              |
|----------------|--------------------------------------------------------------------------|
| Company        | Company responsible for the space mission                                |
| Location       | Location of the launch                                                   |
| Date           | Date of the launch                                                       |
| Time           | Time of the launch (UTC)                                                 |
| Rocket         | Name of the rocket used for the mission                                  |
| Mission        | Name of the space mission (or missions)                                  |
| RocketStatus   | Status of the rocket as of August 2022 (Active or Inactive)              |
| Price          | Cost of the rocket in millions of US dollars                             |
| MissionStatus  | Status of the mission (Success, Failure, Partial Failure, Prelaunch Failure) |

## Steps Taken
1. ***Data Wrangling***: Initially, data wrangling was performed to handle incorrect data types and ensure consistency across the dataset.

2. ***Handling Missing Values***: The dataset was inspected for missing values, and decisions were made on whether to impute or drop them based on their importance to the analysis.

3. ***Exploratory Data Analysis (EDA)***:
   - Utilizing SQL (SQLite3) to query the dataset for insights.
   - Visualization with various plots such as bar plots and line plots to visualize launch trends over time, identify the most active countries in space missions, and understand mission success/failure rates.
   - Analyzing the distribution of rocket types to determine the most frequently launched ones and investigating potential reasons behind their popularity.

4. ***Geospatial Analysis with Folium***:
   - Employing Folium to create an interactive map showcasing the four major launch bases.
   - Marking each launch base on the map and indicating the number of launches performed from each site.
   - Investigating the geographical placement of launch bases to understand the rationale behind their locations.

## Conclusion
Through this analysis, I've gained valuable insights into the trends and patterns of space missions over the years. The combination of SQL queries, data visualization, and geospatial analysis provided a comprehensive understanding of the dataset, shedding light on various aspects of space exploration.



