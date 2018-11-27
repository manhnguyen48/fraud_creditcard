# Credit card fraud detection
Credit card fraud detection from kaggle datasets

The dataset is from kaggle: <a>https://www.kaggle.com/mlg-ulb/creditcardfraud/home</a>

Algorithm used: XGB binary:logistic

Parameters: 
{'colsample_bytree': 0.1,
 'gamma': 0.0,
 'learning_rate': 0.2,
 'max_depth': 7,
 'min_child_weight': 5,
 'n_estimators': 500,
 'reg_alpha': 0.1,
 'subsample': 0.55}
 
 Eval metrics: Area under precision recall curve
 
 Tuning time: 45 minutes. 10 samples over 5 cross validation. 
 
 Training time: 29 sec, train-aucpr:0.999994	eval-aucpr:0.883845
 
 Metrics: 
 <ul>
  <li>Accuracy: 0.999</li>
  <li>Precision: 0.888 </li>
  <li>Recall: 0.8163 </li>
  <li>F1: 0.85 </li>
 </ul>
