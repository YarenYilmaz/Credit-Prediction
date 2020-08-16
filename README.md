# Credit Prediction for Selected Customers

The goal of the project is catching the similar customers when any customer starts the credit application steps in the digital banking platforms and predict the best credit amount for the selected customers

## Steps
1. If a customer starts the credit application steps on the digital banking platforms , the most similar customers are found. (for now; the most similar 1 customer is found)
   - K-Means jupyter notebook file and customer_data_genv2 data file is for step 1
   - K-Means is used with K=4
   - Split customers into clusters
   - Assign the customer who makes a transaction into a cluster
   - Find the most similar customer in the selected cluster
2. In this problem, the target variable is numerical, so regression technique is preferred. For credit prediction, different regression models are applied.
   - Regression jupyter notebook file and customer_data_genv3 data file is for step 1
   - K Nearest Neighbour
   - Linear regression
   - Decision Regression Tree
   - Random Forest


## Result
After the comparison of runtimes and mean absolute errors, the Random Forest algorithm is chosen.


