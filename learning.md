# math score, studens performance prediction

## Avoid multicollinearity among dummies
with the get_dummies pandas method, apply drop_first=True to avoid the multicollinearity

## how to use the r2_score sklearn metric
## how to mapping integers on categorical features 

## Scaled data, coefficients and residuals analysis
when we work with linear regresion and logistic regresion models and wants to interpret the coefficients (B_i) it is recommended to scale the numerical data

coefficients (B_i) interpretation:
- positive coefficient:
    - When the variable increases, the prediction also increases. 
- negative coefficient:
    - When the variable increases, the prediction tends to decrease. 
- the absolute value of the coefficient:
    - greater impact on the prediction
- a little absolute value of the coefficient:
    - the variable has a lesser impact on the prediction.


* talk about the error, i scaled the data before split the trin and test set
* when we train a linear regresion model with scaled data is normal to reduce the r2_score a little (+-0.05)
