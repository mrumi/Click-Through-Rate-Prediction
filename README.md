# Click-Through-Rate-Prediction

Data Source: Kaggle

Preprocessing: The dataset has 21 features after excluding id and hour. Some of these features have too many unique values. Features which have more than 1000 unique values are excludeed. Based on the number of unique values each feature has been converted to a vector of size 12 or 16 when it has too many unique values or the same size as the number of unique values it has. Data is preprocessed in process.py.

GD/SGD: timer.py compares between gradient descent and stochastic gradient descent to check which algorithm would perform better to predict result. The result is captured in graph.png 

SGD+L2 Regularization: Initially some parameters are tuned using 30K randomly sampled data to be used as training and 10K data as validation set. Tuned paras are number of iterations, step and batch fraction. The model is optimized using L2 regularization with stochastic gradient descent. ctr.py is code for this whole process. 


