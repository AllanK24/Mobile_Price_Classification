# This is the solution for Mobile Price Classification [https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification] task dataset available on Kaggle.

### Note: test.csv wasn't used, you can test it yourself. Original train.csv was split into 1800 examples for training and 200 examples for validation

For this task 10 different supervised learning algorithms were utilized:
1) Tensorflow Implementation of Neural Network
2) Decision Tree
3) Random Forest
4) SVM
5) XGBoost
6) Naive_Bayes
7) Logistic Regression for Multi Class Classification
8) K-Nearest Neighbor
9) Gradient Boosting Machine
10) Ada Boost

Optimal hyperparameters for all algorithms were found using Scikit Learn's `GridSearchCV` and `RandomizedSearhCV`.
Additionally, `StandardScaler` was used to scale the following features:
- battery_power
- px_height
- px_width
- ram