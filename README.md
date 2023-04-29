# Predicting Fetal Health

Cardiotocography is a powerful tool that is mainly used to determine how much oxygen the fetus is receiving, which is crucial for development. Classification models decision tree, support vector machine, gradient boost, k-nearest neighbors and logistic regression were applied to a multi-class dataset predict fetal health. 10-fold cross validation was used along with a grid search to perform hyper-parameter tuning. It was determined that gradient boost was the best performing model given this dataset, with a 0.99 value for area under the ROC curve. 


## Preprocessing and Exploratory Data Analysis
### Box-Plots
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/box_plots.png" width="700" />

### Normalized Box-Plots
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/norm_box.png" width="600" />

### Histograms
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/hist.png" width="700" />

### Correlation Matrix
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/corr_matrix.png" width="700" />

### Principal Component Analysis
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/pca.png" width="700" />


## Results
### Decision Tree Classifier
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/dt_metric.png" width="500" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/dt_param.png" width="700" />

### Support Vector Machine
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/svm_metric.png" width="500" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/svm_param.png" width="700" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/svm_boundary.png" width="500" />

### Gradient Boosting
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/gb_metric.png" width="500" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/gb_param.png" width="700" />

### k-Nearest Neighbors
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/knn_metric.png" width="500" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/knn_param.png" width="700" />

### Logistic Regression
<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/logreg_metric.png" width="500" />

<img src="https://github.com/dgambone3/CSC6740DataMiningProject/blob/main/imagees/logreg_param.png" width="700" />

