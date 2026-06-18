# Basketball Injury Recurrence Prediction

## Project Overview
This project predicts basketball injury recurrence using biomechanical, injury, and rehabilitation data. The analysis applies a random forest classification model to identify whether a player is likely to experience injury recurrence based on physical, injury-related, and recovery-related predictors.

Originally completed as a group course project. This repository is organized as a portfolio version by Lana Robison to highlight the modeling workflow, evaluation process, and documentation.

## Tools Used
- R
- Quarto
- tidymodels
- tidyverse
- ranger
- vip
- ggplot2

## Methods
- Cleaned and encoded categorical predictors
- Removed non-modeling identifier and date fields
- Split data into training and testing sets
- Tuned a random forest classifier using cross-validation
- Evaluated classification accuracy on training and testing data
- Used variable importance to interpret key predictors
- Explored principal component analysis for potential dimensionality reduction

## Key Results
The random forest model achieved high training accuracy but lower testing accuracy, indicating overfitting. The model reached approximately 96.2% training accuracy and 65% testing accuracy. Variable importance results suggested that biomechanical and rehabilitation-related variables were important predictors of recurrence.

Important predictors included:
- Knee angle
- Jump height
- Rehabilitation efficiency score
- Ankle flexion
- Reaction time

## Limitations
The model showed evidence of overfitting, meaning it captured training patterns that did not generalize as well to unseen data. Future improvements could include using additional evaluation metrics such as ROC AUC, sensitivity, specificity, and precision, along with simplified models or dimensionality reduction.

## Repository Structure
- `analysis/`: Quarto source file for the analysis
- `data/`: project dataset
- `docs/`: notes on data and modeling approach
- `report/`: rendered project report PDF

## Portfolio Relevance
This project demonstrates machine learning classification, model tuning, train/test evaluation, overfitting diagnosis, feature importance interpretation, and clear communication of model limitations.
