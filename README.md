# Santander-Customer-Satisfaction

This project uses Santander Bank's dataset to forecast the chance that each test set client is dissatisfied. 
With the data, a supervised learning classification model can anticipate customer unhappiness. Evaluate the 
viability of numerous customer satisfaction prediction measures. Using model interpretation, we find 
consumer satisfaction variables. Identify possible areas for improvement and model implementation. We 
start with performing routine Data cleanup & EDA, followed by PCA (Principal Component Analysis) to 
reduce the dimensionality of the data and help in training data faster. Further, we check for class imbalances 
(As we are working with customer satisfaction data, we expect there to be a natural imbalance). We use 
Logistic Regression, Random Forest classifier, and XGBoost as base models, while also tuning their 
hyperparameters, creating an ensemble model combining the base models, and checking the cumulative 
accuracy of the model. After establishing the best model, we use permutation importance to determine the 
predictors with the influence on model performance.
