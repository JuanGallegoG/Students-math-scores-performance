# math score, studens performance prediction

## Description
with the knowledge about EDA and basic machine learning train a model to predict
the students math scores

## Dataset
- By: [kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- principal variables: "gender","race/ethnicity","parental level of education","lunch","test preparation course","math score","reading score","writing score"

## realizing steps in this project

1. cleaning data
    - apply get_dummies pandas method to change categorical variables.
    - change gender feature into numerical type (female: 1, male: 0).
    - Assign integer values to the educational level of parents from 1 to 5 to create a hierarchy.

2. baseline model
    - model: linearRegression
    - divide the data into test, training to train the model, and validate predictions.
    - try the model precission with the  sklearn R2_score metric

## conclusions

the model has an R2_score of 0.88, thats is a higher score.

## Next step
try to improve the model looking for others algorythms or modified variables and try other metrics to evaluate the model.

