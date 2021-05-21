# Decision Tree

## Dataset utilized- Rainfall for the Indian States
According to the dataset we have chosen for this classification problem, it contains the information about the rainfall (in cm) from Jan to Dec for different states. Here, State is the class to be predicted. We are predicting the name of the state by seeing the variation in rainfall patterns. 
Number of Instances: 641 
Number of Attributes: 10 
 
|Library|Function|Usage| 
|-------|-------|------|
|Pandas |	read_csv, DataFrame| to read the dataset| 
|NumPy 	|Mean 	|to calculate mean |
|Seaborn |	heatmap, distmap |	to visualize relationship b/w dependent & independent variable| 
|sklearn.model_selection |	train_test_split| 	to partition the dataset  |
|Sklearn.model_selection |	Cross_val_score |	For cross validation |
|Sklearn.tree |	DecisionTreeClassifier 	|To fit Decision Tree model |
|sklearn.metrics |	confusion_matrix, accuracy_score |	To obtain confusion matrix and calculate accuracy| 
 
Results- 
-
30-fold cross validation using NB 
|Iteration|Accuracy|
|---|--------------------|
|1  |  0.5675675675675675| 
|2  |  0.5151515151515151|
|3  |  0.7241379310344828| 
|4  |  0.7037037037037037 |
|5  |  0.6538461538461539 |
|6  |  0.6538461538461539 |
|7  |  0.6 |
|8  |  0.56 |
|9  |  0.8095238095238095 |
|10 |  0.55 |
|11 |  0.7647058823529411| 
|12 |  0.5882352941176471 |
|13 |  0.6470588235294118 |
|14 |  0.6666666666666666 |
|15 |  0.5333333333333333 |
|16 |  0.6666666666666666 |
|17 |  0.5384615384615384 |
|18 |  0.5833333333333334 |
|19 |  0.8888888888888888 |
|20 |  0.75 |
|21 |  0.5 |
|22 |  0.875| 
|23 |  0.6 |
|24 |  0.5 |
|25 |  0.5 |
|26 |  0.5 |
|27 |  1.0 |
|28 |  1.0 |
|29 |  1.0 |
|30 |  1.0 |
  
Mean Accuracy  0.6813375754007939 

Interpretation-
-
Considering the above 30-fold cross validation results, Decision Tree is not the appropriate mode l for the given dataset. Although 68.13% mean accuracy is decent but one possible reason could be the high number of labels in the class and comparatively less number of instances for each lab el which make it unsuitable. 
