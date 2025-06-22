# BigData-final-project

# Project Title

Restaurant Safety in NYC

## Project Description
In this big data analysis project we computed how restaurant safety in New York City changes in time between 2015 and 2022, and how it compares between different chain restaurants and non-chain restaurants.  We later presented this project in the form of poster on InnoFest of National Chengchi University.


## Getting Started

The data about restaurant inspection results were downloaded from Kaggle, the original sourced from NYC Open Data, providing large dataset containing almost 300,000 rows included virtually all restaurants in NYC. Data in CSV format were downloaded in R studio and analysed by our team. 

## File Structure

There are three main parts - ici project template, read me and code compiled from all memebers of the team.  The link to the data used in our project can be found in the readme.

## Analysis

Data were analysed using the R language. In a first step we used the date column to separate the compute the number of of inspections and their results by different months and years, and later we compared the distribution of values between diferent time periods using the box plots as well as bar chart and tables. In the second step, we used the restaurant location to separate restaurants into chain and non-chain restaurants, and compared their distribution using both boxplots and bar chart. Table of descriptive statistics of both option was also created allowing for comparison. As for the very last part of our analysis, we sorted out the top 20 biggest chain restaurants and compared their rating using boxplots, while also computing the the different number of of critical flags.

## Results
We found that over the years the safety of restaurants in NYC was actually getting worse, with an exception of 2020. Hovewer after the coronavirus the restaurant safety got rapidly worse, creating a clear upward trend. Safety also fluctuates with months, with summer and autumn being the least safe. Chain restaurants are generally slightly more safe than non-chain restaurants, however they tend to have a slightly higher number of non-serious violations and lower number of serious violations. Out of the twenty biggest chain restaurants in New York, the one with the most serious violations (highest count of critical flag) was Dunkin, followed by Subway and McDonalds.

## Contributors

Petra Nepozitkova _ project manager and head data analyst
Camille Mercher  - data analyst
Rachel Xu 許瑈芸 - data analyst
Zhenhao Li - researcher
Oscar Grau Gesa - data analyst and poster designer


## References
Data source: https://www.kaggle.com/datasets/minisam/new-york-city-restaurant-inspection20172021?select=DOHMH_New_York_City_Restaurant_Inspection_Results.csv

https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data
