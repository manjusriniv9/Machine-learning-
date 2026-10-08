**BIAS VARIANCE TRADE OFF**

Bias and variance are two key concepts that explain the errors a machine learning model can make during prediction. A good model should not only perform well on training data but also generalize well to unseen data. Understanding these concepts helps determine whether a model is too simple or too complex.

Bias: Error caused by overly simple assumptions in the model, which may lead to underfitting.
Variance: Error caused by the model being too sensitive to training data, which may lead to overfitting.
Goal: Balance bias and variance so the model captures patterns while still generalizing well to new data.

Bias Variance Tradeoff
The bias variance tradeoff describes the balance between a model being too simple and too complex. A simple model may miss important patterns (high bias), while a very complex model may learn noise from training data (high variance). The aim is to balance both so the model performs well on new data.

Simple models usually have high bias and low variance, which may cause underfitting.
Complex models usually have low bias but high variance, which may cause overfitting.
Balanced model achieves an optimal point where both bias and variance are reasonably low.
Goal of machine learning is to minimize the total prediction error on unseen data.

Total Error = Bias ** 2 +Variance+IrreducibleError

Methods of Bias Variance Trade off

1. Cross Validation - is a way to estimate how well a model will perform on unseen data, using only your training data. Instead of trusting one train/test split, you split the data several times, train and evaluate each time, and average the results.

<img width="2720" height="1240" alt="five_fold_cross_validation" src="https://github.com/user-attachments/assets/9b286da3-5820-4a7b-9db6-f7841ebe472a" />

  Types of Cross Validation 
   1. Hold out
   2. Leave One cut validation
   3. Stratified K-fold
   4. Time series Split

2.Regularization: Reduce the variance ( reduce the noise in the data which helps Overfitting)




  Types of Regularisation: 
  1. Ridge
  2. Lasso
  3. Elastice net


3.Feature Selection:




  Types of feature selection:
  1. Filter
  2. Wrapper
  3. Embedded


4.Ensemble methods



  Types of Ensemble methods
  
  1. Bagging - Bagging, Random forest, extra trees
  2. Boosting - Adaboost, gradient boosting, XGBoost, lightGBM
  3. Stacking



