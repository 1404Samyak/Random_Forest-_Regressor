This is car prediction solved using Random Forest Regressor along with hyperparameter tuning 
The metrics is compared with other regressor models like RidgeCV,LassoCV,SVR,K Neighbors Regressor ,DecisionTreeRegressor also 
The random forest Regressor provides best accuracy because it uses the bagging ensemble technique.
In bagging dataset is sampled randomly with replacement to form bootstrap samples ,and each bootstrap sample is trained simultaneouly with a base model(a decision tree) and final predicted value is calculated as average outputs of all base models