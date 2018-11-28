# Credit card fraud detection
Credit card fraud detection from kaggle datasets: <a>https://www.kaggle.com/mlg-ulb/creditcardfraud/home</a>

About dataset: 
<ul>
 <li>Highly unbalanced target class (0.17% over nearly 300k transactions)</li>
 <li>Unamed feature space (features are from PCA as described)</li>
 </ul>

Algorithm used: XGB binary:logistic, tree_method = gpu_hist

Parameters: 
{'colsample_bytree': 0.5,
 'learning_rate': 0.2,
 'max_depth': 16,
 'min_child_weight': 1,
 'n_estimators': 550,
 'subsample': 0.75}
 
 Eval metrics: Area under precision recall curve
 
 Tuning time: 1h2m 
 
 Training time: 13.6 sec, train-aucpr:1	eval-aucpr:0.88911
 
 Metrics: 
 <ul>
  <li>Accuracy: 0.99963 </li>
  <li>Precision: 0.96386 </li>
  <li>Recall: 0.81633 </li>
  <li>F1: 0.88393 </li>
 </ul>
