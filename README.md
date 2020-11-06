# Loan-Default-Prediction
This is a qualification hackathon for the Data Science Nigeria AI Bootcamp 2020

# Data Science Nigeria AI Bootcamp Competition

A Repo of my solution to the Bootcamp Qualification competition 5th Place Solutuion

Position on Leader Board -- 127th of 750 (Top 20%)

link -- https://zindi.africa/hackathons/dsn-ai-bootcamp-qualification-hackathon

# KOWOPE MART Bootcamp Competition

Kowope Mart is a Nigerian-based retail company with a vision to provide quality goods,education and automobile services to its customer at affordable price and reduce if not eradicate charges on card payments and increase customer satisfaction with credit rewards that can be used within the Mall.
To achieve this the company has partnered with DSBank on co-branded credit card with additional functionality such that customers can request for loan, pay for goods even with zero-balance and then pay back within an agreed period of time. This innovative  strategy has increased sales for the company. However, there has been recent cases of credit defaults and Kowope Mart will like to have a system that profiles customers who are worthy of the card with minimum if not zero risk of defaulting.
You have been employed as a Data Scientist to leverage Machine Learning to predict customers who are likely to default or not.


## Predict Customers who will default on a Loan

## MY Solution Approach
- A Catboost Model
  - Engineered new Features
  - Used a Stratified Kfold of 15 Splits
- A Light Gradient Boost Model
	- Engineered new Features
	- Used a Stratified Kfold of 15 Splits
- A XG Boost Model
	- Engineered new Features
	- Used a Stratified Kfold of 15 Splits

- Stacking
  - I stacked the 3 previous models using a simple Meta-Regressor.

## Improvement
- Better Feature Engineering
- Domain Knowledge would proved better
- Magic Features
- Hyper Parameter Tunning: I used a cpu all through so could not do much on that
- Feature Interaction
- Feature Selection
