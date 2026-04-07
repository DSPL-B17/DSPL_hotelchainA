# DSPL_hotelchainA
# Hotel Chain A – Booking Cancellation Prediction

## Project Overview
This project was developed for Hotel Chain A, a hospitality group under OCTAVE 
— the Data and Advanced Analytics division of the John Keells Group. The goal 
is to analyse historical booking data to identify cancellation patterns, quantify 
revenue loss, and build predictive models to estimate the probability of booking 
cancellations and no-shows across City, Airport, and Resort hotels.

## Problem Statement
Hotel Chain A experiences significant revenue loss due to booking cancellations 
and no-shows. This project moves from descriptive insights to predictive and 
actionable intelligence to support operational and commercial decision-making.

## Methodology
1. Data Preparation — Cleaning, handling inconsistencies, feature engineering
2. Exploratory Data Analysis — Univariate, bivariate and multivariate analysis
3. Revenue Loss Analysis — Quantifying financial impact by hotel type, booking 
   channel, deposit type, demographics and lead time
4. Predictive Modelling — Five machine learning models trained and evaluated

## Models Used
| Model | Description |
| Decision Tree | Interpretable baseline model with hyperparameter tuning |
| Logistic Regression | Linear baseline with L2 regularisation |
| Random Forest | Ensemble model — selected as final model |
| XGBoost | Gradient boosting with regularisation |
| Neural Network | Deep learning with dropout and batch normalisation |

## How to Run
1. Clone the repository
2. Upload datasets to your Google Drive under `DSPL/GCW/Data/Raw/`
3. Run `Hotel_Chain_A_Analysis.ipynb` first to generate cleaned datasets
4. Run any model notebook from `DSPL/GCW/Data/Processed/`
