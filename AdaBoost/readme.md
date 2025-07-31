#### All the rights reserved for the IBM Machine Learning Certificate
- This series of projects is my implementation / Pracital exercise using some notebooks and adding variations of what I have seen from IBM

# Purpose:
- Conducting a detailed evaluation of AdaBoost classifiers using different numbers of estimators and learning rates, tracking both training and testing accuracy. 
- The goal is to understand how AdaBoost behaves with different base estimators and algorithms

### Accuracy Function
- This evaluates and returns the accuracy on both training and testing sets using accuracy_score.

### Boosting Experiment Function
- Tests different values of:
- n_estimators (from 1 to 99)
- learning_rate (default [0.2, 0.4, 0.6, 1])
- Repeats the experiment multiple times (times = 20)
- Trains an AdaBoostClassifier on each combination
- Records and averages accuracy across runs
- Prepares for plotting performance curves

### Expected Outcome
- Training and Testing accuracy curves vs. number of estimators
- For different learning rates
- Possibly identifying overfitting or underfitting patterns