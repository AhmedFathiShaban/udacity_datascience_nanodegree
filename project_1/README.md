# Analysis Of `Seattle Airbnb Open Data` Dataset

## This project is part of the udacity data-science nanodegree program.

## 1.0. Motivation
### In this project, my aim is to gain some insights from the AirBnB Seattle Dataset.
### Specifically, there are three main questions I would like to answer : 
(Q1) As a real-estate company that sells houses in Seatle, where should I focus my marketing campaigns ? Assume we have a budget for campaigns in 10 different locations.

(Q2) As a place owner in seattle, which renting model should I use to maximize my average profit ?

(Q3) As a tourist who travels alone with low budget and flexibility of free time, which month of the year would be cheapest for me to have a vacation in Seatle ? Also which neighbourhood should I target if I am not so picky ?

## 2.0. Libraries Used 
* pandas (1.1.5)
* matplotlib (3.3.3)

## 3.0. Files in the repo

The main file in the repo is `udacity_datascience_project_1.ipynb`. This file includes all the analysis performed on the dataset, as well as tables and visualizations for all the results.

The dataset itself is the combination of  `calendar.csv`, `reviews.csv`, and `listings.csv` . Originally downloaded from [here](https://www.kaggle.com/airbnb/seattle).

## 4.0. Main Results

(Q1) As per my analysis, the answer to the first question turned out to be that the real estate company should focus most of its effort (87.37%) in Seattle itself, followed by Spokane, Washinton and Kent, Washinton.

(Q2) I could not reach a reasonable answer to the second question, as the dataset does not have sufficient information for such analysis. Specifically, the data does not have information regarding whether a specific place was actually rented or not at every specific date, and hence, analysis based on maximizing yearly profit simply could not be done.

(Q3) The Data shows that the cheapest possible option would be Magnolia in January, with an average nightly price per person of $36.65. That shoud be our recommendation for the tourist.



