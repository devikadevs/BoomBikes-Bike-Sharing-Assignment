# BoomBikes - Bike Sharing Assignment
> Outline a brief description of your project.

## OBJECTIVE
> The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## The steps we will follow in the exercise is as follows:
* Reading, understanding and visualising the data
* Preparing the data for modelling(train-test split, rescaling etc)
* Training the model
* Residual Analysis
* Predictions and Evaluation on the test set

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Essentially, the company wants to evaluate — 
1. Which variables are significant in predicting the demand for shared bikes
2. How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Points To Note
- Dropped a few insignificant columns
- For Feature scaling, I have used MinMax Scaling
- For building our model, we will be using the LinearRegression function from SciKit Learn for its compatibility with RFE (which is a utility from sklearn) and then dropping insignificant variables in presence of other variables.
- Model 6 is our final model and we have considered p-value and VIF to decide on feature elimination
- Error terms are normally distributed

## Conclusions
- Conclusion 1 - cnt vs temp has a strong positive correlation
- Conclusion 2 - 2019 marked a higher demand for shared bikes
- Conclusion 3 - weather conditions affect the bike rentals
- Conclusion 4 - R-square, Adjusted R-squared and F-statistic) and there are no multi collinear (high VIF) variables
- Conclusion 5 - For the training set, the P-value for all the features is almost 0.0 and R2 is 0.830 which is significantly high and Prob (F-statistic) is 0.00000283
- Conclusion 6 - Overall we have a decent model, R2 on test set is 79% which is pretty close to training set R2. it indicates stability- What model has learnt on training set, it can generalise well on test set

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@devikadevs] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
