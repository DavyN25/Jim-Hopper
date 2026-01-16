# Jim-Hopper

## Team Members:
Helena Sospedra
Rui Parreira
Davy Goupil 
Ghazal Hassanzadeh

# Project Overview

This project uses the UCI Bike Sharing Dataset (Capital Bikeshare, 2011–2012) to forecast daily bike rental demand using weather, seasonal, and calendar features. The goal is to help a new bike-sharing startup make data-driven decisions about launch timing, initial capacity, and operational risk. The team compares several machine learning models and finds that ensemble methods, such as Random Forest, outperform simple linear models for predicting demand. The results support strategic planning by highlighting key demand drivers (especially temperature) and identifying high- and low-demand periods across the year. 

## Introduction

Bike-sharing systems have become an increasingly important component of sustainable urban mobility, offering flexible and environmentally friendly transportation options in cities worldwide. For a new bike-sharing startup, entering a market involves significant uncertainty — particularly regarding demand levels, seasonal fluctuations, and operational risk. Decisions such as when to launch, how many bikes to deploy, and how sensitive demand is to external conditions must often be made before any internal historical data is available.

This project explores how historical bike-sharing data can be leveraged to support data-driven decision-making for new market entrants. Using daily bike rental data combined with weather, seasonal, and calendar information, the goal is to understand demand patterns and develop a machine learning model capable of predicting daily bike rental demand. Such predictions can help a startup assess market viability, anticipate periods of high and low demand, and plan initial capacity more effectively.

By focusing on daily demand forecasting, this project balances predictive accuracy with interpretability and business relevance. The analysis follows a structured machine learning workflow including data cleaning, exploratory data analysis, feature engineering, and model development. The findings are interpreted from a business perspective, highlighting how predictive analytics can reduce uncertainty and support strategic planning for a bike-sharing startup.


## Research Questions & Business Objectives

To support a data-driven market entry strategy for a new bike-sharing startup, this project focuses on understanding demand patterns, operational risks, and strategic timing. The following research questions guide the analysis and modeling process:

---------------------------------
### RQ1: Key Demand Drivers & Weather Sensitivity

Business Objective: Identify the factors that most strongly influence bike rental demand.
Research Question: Which weather and seasonal factors most strongly influence daily bike rental demand, and how sensitive is demand to changes in temperature, humidity, and wind speed?

-----------------------------------
### RQ2: High vs Low Demand Periods (Risk Awareness)

Business Objective: Reduce operational and financial risk by identifying demand extremes.
Research Question: Can periods of high and low demand be identified and characterized based on predicted daily bike rentals?

-----------------------------------
### RQ3: Optimal Market Entry Timing

Business Objective: Support strategic launch planning for a new bike-sharing service.
Research Question: When is the optimal time of year to launch a bike-sharing service to maximize early adoption?

-----------------------------------
### RQ4: Capacity Planning & Usage Patterns

Business Objective: Provide guidance for initial bike deployment and operational planning.
Research Question: How many bikes should be deployed on a typical day to avoid shortages or overcapacity, and how do demand patterns differ between weekdays and weekends?


## Dataset Selection 

We used the Bike Sharing Dataset from the Capital Bikeshare system (2011–2012), which includes hourly and daily counts of rental bikes along with weather and seasonal variables.

https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

It contains 17,389 instances and 13 features, making it suitable for regression tasks.
The dataset was mostly clean, but we performed additional cleaning by removing unnecessary columns for model training.


# Workflow

## Tools & Libraries
- Python 3  
- Pandas (data manipulation)  
- NumPy (numerical operations)   
- Trello (project management)  
- GitHub (collaboration)
- Slack Group (Communication)
- Libraries for machine learning in Python


### 1. Project Management
We created a Kanban board on Trello to organize tasks throughout the week:
https://trello.com/b/6FVof5jE/jimhopper

### 2. GitHub Repository
Our main repository is here:
https://github.com/DavyN25/Jim-Hopper

We practiced collaboration through branching, merging, and regular updates.

### 3. Final project presentation
The results of our analysis are available in the project presentation:
https://www.canva.com/design/DAG-OKs7TJ4/xlmRsiYz9Sl9f7WkWXvRKg/edit

This project strengthened our ability to perform collaborative data analysis, reason from an investment perspective, and train machine learning models in Python.


# Project Chronology 

## Day 1 - Project Initiation & Data Selection
Selected the dataset and analyzed its structure for machine learning suitability

## Day 2 – Clean and wrangle data 
On Day 2 we cleanead the data, choosing the collumns suitable for Machine Learning models.
Cleaned the data, selecting columns suitable for machine learning models.

Began feature engineering:
Label encoding
Feature scaling and selection
Used KNN for initial testing (80/20 train-test split).


## Day 3 - Supervised Learning
Refined our models using:
Linear Regression (80/20 split)
Decision Tree Regressor
KNN

Began drafting the presentation on Canvas.


## Day 4
Focused on model fine-tuning. Removed KNN due to poor performance.
Re-split the dataset into categorical and numerical columns, applied One-Hot Encoding, and focused on Linear Regression, Decision Tree and Random Forest.
Performed hyperparameter tuning with Grid Search.


## Day 5 – Project Presentation
Presented our findings and proposed a business plan based on the forecasts.


## Analysis & Conclusions

### Key Findings and Insights

Temperature is the most important driver of bike demand.

Ensemble models (e.g., Random Forest) outperform linear models.

Weather variables like humidity and wind influence demand, but less than temperature.

Calendar features (season, weekday) affect demand stability rather than daily spikes.


### Future Work and Improvements
The dataset could be expanded with business-oriented features such as:

Rental price and earnings

Revenue per rental and profit margin

Price elasticity indicators

Adding location-level data (station or neighborhood) could allow:

Identification of high-demand hotspots

Optimized bike allocation per area

With more time, we could test alternative models, perform deeper hyperparameter tuning, and provide sharper insights into optimal launch timing.



## Challenges in the Project

Choosing the most appropriate predictive model.

Dealing with columns that caused overfitting.

Initially not separating categorical and numerical features properly.

Some models showed inconsistent or illogical predictions.


