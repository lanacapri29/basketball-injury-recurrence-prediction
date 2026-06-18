# Modeling Notes

## Objective
Predict whether a basketball player experienced injury recurrence using injury, rehabilitation, and biomechanical predictors.

## Model
A random forest classification model was selected because it can handle nonlinear relationships and mixed predictor types after preprocessing.

## Evaluation
The model was evaluated on both training and testing data. The model achieved high training accuracy but lower testing accuracy, indicating overfitting.

## Interpretation
Variable importance was used to identify influential predictors. The most important variables included knee angle, jump height, and rehabilitation efficiency score.

## Future Improvements
Potential improvements include:
- Evaluating ROC AUC, sensitivity, specificity, and precision
- Simplifying the model to reduce overfitting
- Testing logistic regression or penalized classification models
- Applying PCA or other dimensionality reduction methods before modeling
- Increasing the sample size if additional data becomes available
