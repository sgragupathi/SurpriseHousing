# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company is looking at prospective properties to buy to enter the marketusing data analytics/ML.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
-To model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
- Required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:1) Which variables are significant in predicting the price of a house. 2) How well those variables describe the price of a house. 3) determine the optimal value of lambda for ridge and lasso regression
- Dataset file train.csv which contains 81 features about house, quality, built year, gargage, sold, neighborhood, area, bathroom numbers, etc.,

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge and Lasso regression model has used to predict the signigicant variables.
- Lasso model works better than Ridge here. Difference between train vs test R2 score is less on Lasso model and feature selection helps to identifies the improtant features.
- Optimal value of lambda(hyperparamter) for Ridge model is 8 and for Lasso - 0.001


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy                         1.24.3
- pandas                        1.5.3
- seaborn                       0.12.2
- matplotlib                    3.7.1
- scikit-learn                  1.2.2
- statsmodels                   0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is an assignment for machine learning module as part of upgrad curriculam.
- Refered all online contents of Upgrad and live sessions and tutors.
- This project was based on https://learn.upgrad.com/course/4705/segment/27807/265961/812435/4081307


## Contact
Created by [@sgragupathi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->