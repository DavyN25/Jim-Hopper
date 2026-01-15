# Jim-Hopper

## Team Members:
Helena Sospedra
Rui Parreira
Davy Goupil 
Ghazal Hassanzadeh

# Project Overview

## Introduction

Bike-sharing systems have become an increasingly important component of sustainable urban mobility, offering flexible and environmentally friendly transportation options in many cities. For a new bike-sharing startup, entering a market involves significant uncertainty, particularly regarding demand levels, seasonal fluctuations, and operational risk. Decisions such as when to launch, how many bikes to deploy, and how sensitive demand is to external conditions must often be made before any internal historical data is available.

This project explores how historical bike-sharing data can be used to support data-driven decision-making for a new market entrant. Using daily bike rental data combined with weather, seasonal, and calendar information, the goal is to understand demand patterns and develop a machine learning model capable of predicting daily bike rental demand. Such predictions can help a startup assess market viability, anticipate periods of high and low demand, and plan initial capacity more effectively.

By focusing on daily demand forecasting, this project balances predictive accuracy with interpretability and business relevance. The analysis follows a structured machine learning workflow, including data cleaning, exploratory data analysis, feature engineering, and model development. The findings are interpreted from a business perspective, highlighting how predictive analytics can reduce uncertainty and support strategic planning for a bike-sharing startup.


## Research Questions & Business Objectives

To support a data-driven market entry strategy for a new bike-sharing startup, this project focuses on understanding demand patterns, operational risks, and strategic timing. The following research questions guide the exploratory analysis and modeling process:

---------------------------------
### RQ1: Key Demand Drivers & Weather Sensitivity

Business Objective:
Identify the factors that most strongly influence bike rental demand.

Research Question:

Which weather and seasonal factors most strongly influence daily bike rental demand, and how sensitive is demand to changes in temperature, humidity, and wind speed?

-----------------------------------
### RQ2: High vs Low Demand Periods (Risk Awareness)

Business Objective:
Reduce operational and financial risk by identifying demand extremes.

Research Question:

Can periods of high and low demand be identified and characterized based on predicted daily bike rentals?

-----------------------------------
### RQ3: Optimal Market Entry Timing

Business Objective:
Support strategic launch planning for a new bike-sharing service.

Research Question:

When is the optimal time of year to launch a bike-sharing service in order to maximize early adoption?

-----------------------------------
### RQ4: Capacity Planning & Usage Patterns

Business Objective:
Provide guidance for initial bike deployment and operational planning.

Research Question:

How many bikes should be deployed on a typical day to avoid shortages or overcapacity, and how do demand patterns differ between weekdays and weekends?

## Dataset Selection 

We used the database fir Bike Sharing
This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.

https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

It have 17.389 Instances and 13 Features, so we can test it on Regression tasks. 

The original dataset was almost clean, but we cleaned it using several techniques, dropping the collumns that were not needed for the machine training. 


# Workflow

## Tools & Libraries
- Python 3  
- Pandas (data manipulation)  
- NumPy (numerical operations)   
- Trello (project management)  
- GitHub (collaboration)
- Slack Group (Communication)

### 1. Created a Kanban Board for Project Management Purposes on Trello.
We organized the tasks between before and after lunch for the whole week. 
https://trello.com/b/6FVof5jE/jimhopper

### 2. Created a Github Repository for the Project:
https://github.com/DavyN25/Jim-Hopper

We created the repository and defined the collaboration status for all group members. We use branch and merge techniques, so all files are always updated. We have practiced working collaboratively on the repository.


### 3. Final project presentation
The results from the analysis can be found in the presentation slides of the project:
https://docs.google.com/presentation/d/1oWkrltrtDz9xgZqZ8cStePZL4h0kxAryEGfsRMhdTBc/edit?usp=sharing

This project helped our team practice collaborative data analysis, investment reasoning, and Python-based machine learning training.


# Project Chronology 

## Day 1 - Project Initiation & Data Selection
On Day 1 we focused selecting the database and analysing for the machine learning project. We've done 


## Day 2 – Clean and wrangle data 
On Day 2 we cleanead the data, choosing the collumns suitable for Machine Learning models.
Started feature engineering:
    - Label Enconding
    - Feature Encoding
    - Feature Scaling
    - Feature Selection
Used KNN Classifier with 20/80 Split

## Day 3 - Supervised Learning
On Day 2 we kept refining our model, trying new models:
    - Linear Regression with 20/80 Split
    - Decision Tree with 20/80 Split
    - Date - Linear Regression / Decision Treen/KNN

Start drafting presentation on Canvas 

## Day 4



## Day 5 – Project Presentation
On Day 5 we presented our findings and pitched the business plan. 





## Analysis & Conclusions


## Challenges in the Project

Choosing the right predictive model
Some collumns add overfeed the predictive results, that have been dropped. 


