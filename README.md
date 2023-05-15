# ML-HyperparameterTuning-ModelSelection
Hyper Parameter Testing and Best Model Selection using various methods
In this code I have looked into,
1) how to hyper tune machine learning model parameters 
2) choosing the best model for given machine learning problem
First comparing traditional train_test_split approach with k fold cross validation. Then used GridSearchCV to run K Fold cross validation with its convenient api. Also used RandomizedSearchCV as a replacement for GridSearchCV.
GridSearchCV helps find best parameters that gives maximum performance.
RandomizedSearchCV is another class in sklearn library that does same thing as GridSearchCV but without running exhaustive search, this helps with computation time and resources. 
At last using GridSearchCV to choose best model among all the classification algorithms.
I used digits dataset which is already available in sklearn.datasets.
