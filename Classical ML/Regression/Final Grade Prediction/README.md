# Student Final Exam Grade Prediction

## Problem Statement:
Predicting the final exam grade for secondary students given their attributes such as student grades, demographic, social, and school-related features. This helps the school management to group students and give them tailored learning exercises to improve their final exam grades.

## Data Description
The data contains 33 variables and of which G3 (grade for final exam) is the Target variable. The complete data dictionary can be found here.

## Tasks
1. Find top 3 highly correlated numerical and categorical features with the target variable.
2. Numerical Features (using correlation)
3. Categorical Features (How do you find the correlation between categorical vs. numerical variables ?)
4. How do you check outliers in each column? Create a function that takes in each column and caps the value in the Inter Quartile Range (effectively removing outliers).
5. Analyze the below hypotheses and find insights.
5.1 Does a parent's job have any impact on the final grade?
5.2. Does travel time & study time affect the final grade?
5.3. Impact of Internet access at home on the final grade
6. Is there any multi-collinearity among the features? If so, how do you find and remove those variables? (Hint: VIF)
7. Create new features based on the EDA
8. Build Regression models to predict the final exam grade 
9. Compare the test RMSE/MAE between Linear regression vs. Ridge/Lasso regression to understand the importance of regularization and how it affects the model generalization.
