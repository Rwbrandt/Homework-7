# Yen Settlement Analysis

-----

## Time-Series Analysis

### Procedural Summary

### Evaluation
#### Purchase Potential?

#### Risk?

#### Model Confidence?
------

## Linear Regression Analysis

### Procedural Summary

Pulling in the data of Yen changes and settle prices for the past 30 years allows for a more acurate prediction of future prices.  

The first step is to show the percent return of the Yen and show the change day over day.  After determining that amount, it is possible to formulate the lagged returns to show the comparison of each day side by side.

At this point it is important to split the data up into the testing and training data, I decided to use data prior to 2017 as the training and data from 2018-2019 as the testing data.  

Fitting the training and testing data to a simple regression model, predictions are able to be made about the potential future of the Yen

### Sample Performance Evaluation

The analysis performed above allows for accuracy tests to be run on both the training and testing data to determine the legitimacy of these models.  

Creating the accuracy tests for the two datasets included taking the mean square roots of the data results.  The results of these tests showed that the training sample has the higher RMSE than the testing data.  This shows that the testing data is more accurately predicted than the training data fit on the same model.  This means that the model has a solid capability of predicting how the Yen will move during international business events.