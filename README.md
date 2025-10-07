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
    - change gender feature for numerical type (female: 1, male: 0).
    - mapping the parental level of education feature to set integers since 1 until 5 to create hierarchy.

2. baseline model
    - model: linearRegression
    - split data in test, train for training and predictions
    - try the model precission with the R2_score sklearn metric

## conclusions

the model has an R2_score of 0.88, thats is a higher score.

## Next step
try to improve the model looking for others algorythms or modified variables and try other metrics to evaluate the model.

