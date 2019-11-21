# AmExpert-2019
Predictive modelling on coupon redemption.

Applied tree based ML algorithms (Catboost , Xgboost) in a weighted average(determined by a LR model) ensemble of models to predict the probability of customers redeeming a given discount coupon.
Got best results with a cross validation strategy of random shuffling the given ‘campaign ids’ between train and test data to reduce chances of data leakage.

Metric : ROC-AUC 
