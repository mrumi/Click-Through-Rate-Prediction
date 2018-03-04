# Click-Through-Rate-Prediction

Data Source: Kaggle

Preprocessing: The dataset has 21 features after excluding id and hour. Some of these features have too many unique values. Features which have more than 1000 unique values are excludeed. Based on the number of unique values each feature has been converted to a vector of size 12 or 16 when it has too many unique values or the same size as the number of unique values it has. process.py is code for data preprocessing.

Method Comparison: timer.py comparesbetween gradient descent and stochastic gradient descent to check which would perform better to predict result. 

