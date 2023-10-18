# Final-Project-Supervised-Learning

## Project/Goals
In this project, I am following the instructions in the 'Supervised Learning - Project' notebook. This project is a single-day project to apply what we have learned about ML, specifically, supervised learning. I will be attempting to create a machine learning algorithm that will identify 
people at risk of diabetes based on the variables given.

## Process

- Visualized the data to identify feature relationships and correlations, find any outliers, check whether the data contains any missing values, ensure the target variable values are well balanced, and just get a good understanding of the dataset being used.
- Removed any missing or incorrect values and outliers from the dataset.
- Split my data into training and testing sections. (80% for training and 20% for testing).
- Since we have a classification problem, I used Logistic Regression and Decision Tree models.
- Fit data into models and evaluated and compared results.

## Results

- Several rows from the dataset were removed due to columns having zeros when they shouldn't. We have seen that Glucose has the highest correlation with whether or not a person has diabetes.
- We have also observed that people with diabetes tend to be older, have a higher glucose level and BMI.
- We found some outliers and removed those neccessary to remove.
- From our models, the Logistic Regression Model gave us a higher accuracy and AUC score, and a lower log loss compared to the Decision Tree Model we created. This means the Logistic Regression Model performed better with our data and returned more accurate results.

## Challenges 
Main challenge has been time as this was a single-day project.

## Future Goals
Use a larger range of machine learning algorithms and compare results. 
