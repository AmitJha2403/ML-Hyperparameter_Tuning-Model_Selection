# ML-HyperparameterTuning-ModelSelection
Hyper Parameter Testing and Best Model Selection using various methods

First comparing traditional train_test_split approach with k fold cross validation. Then used GridSearchCV to run K Fold cross validation with its convenient api. Also used RandomizedSearchCV as a replacement for GridSearchCV. <br>
GridSearchCV helps find best parameters that gives maximum performance. <br>
RandomizedSearchCV is another class in sklearn library that does same thing as GridSearchCV but without running exhaustive search, this helps with computation time and resources. <br>
At last using GridSearchCV to choose best model among all the classification algorithms. <br>
I used digits dataset which is already available in sklearn.datasets. <br>
