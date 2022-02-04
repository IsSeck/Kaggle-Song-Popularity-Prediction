# Kaggle-Song-Popularity-Prediction

This challenge requires a certain set of skills such :
- understanding and using tree base methods such as random forests, gradient-boostings methods;
- handling missing values, data imputation;
- handling (slight) data imbalance;
- carefully using cross validation and to choose the hyperparameters that maximize the generalization performance the models. 

For this challenge, I used Sklearn and pytorch. 

I used Sklearn for the Random Forest, handling the missing values and for 
hyperparameters optimization using RandomSearchCV. 

I used pytorch to train a simple Multi-Layer Perceptron (MLP). The data containing categorical, I used embeddings to allow the 
my MLP to handle those categorical features. The model was able to achieve good performance on the training set but had trouble 
to generalize. The bright side is that I can use this idea on other challenges as an alternative to tree based models. 
