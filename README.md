# Polynomial Regression Machine Learning
This example explains working with polynomail regression and concrete dataset.
Link to the dataset - https://www.kaggle.com/maajdl/yeh-concret-data

Polynomail regression add a degree of couve in the presiction to best fit the data instead of just a straight line.

### Steps:

## 1) Load the Data:
1. Load the data in pandas.
2. This dataset will not get coloumns here but we can add that easily
3. Check the notebook for the code.

## 2) Clean The Data:
 1. As its the easiest problem the dataset doesn't have any Missing or duplicate values.
 2. Althouth there's a scope of work everywhere so we can check for understanding.
 
 ## 3) Feature Selections:
 1. With basic method of correlection we will first try to judge which features we can drop.
 2. We can also play with different method and get different predication scores.
 3. I did try the univariat feature selection.
 4. Ultimately the score was same so, revert back....
 
 ## 4) Split the data:
 1. We need to split the data for training and testing.
 2. The data is split into 70% training and 30% testing.
 
 ## 5) Fit the model:
 1. we use the liner regression model to get predicsitons.
 2. after the fit, use predict method for prediction
 
 ## 6) Prediction score:
 1. there are many ways to check the goodness of model
 2. I have used r2_score to check and the model worked fine.
 
 
 
 Check the code and use for more improvement and share...!!!!!
 
