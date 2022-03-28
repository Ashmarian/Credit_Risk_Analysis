# Credit_Risk_Analysis

## Deliverables / Analysis
# Deliverable 1: Use Resampling Models to Predict Credit Risk
# Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
# Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
# Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

### Deliverables 1: Use Resamplng Models to Predict Credit Risk
* For all three algorithms, the following have been completed:
- An accuracy score for the model is calculated (7.5 pt)
- A confusion matrix has been generated (7.5 pt)
- An imbalanced classification report has been generated (15 pt)

**RandomOverSampler**
- An accuracy score for the model was calculated: 0.8325
- A confusion matrix has been generated <br>
![RandomOverSampler Confusion Matrix](./Images/RandomOverSampler_confusion_matrix.png)

- An imbalanced classification report has been generated <br>
![RandomOverSampler imbalanced classification report](./Images/RandomOverSampler_classification_report.png)

**SMOTE**
- An accuracy score for the model was calculated: 0.8325
- A confusion matrix has been generated <br>
![SMOTE Confusion Matrix](./Images/SMOTE_confusion_matrix.png)

- An imbalanced classification report has been generated <br>
![SMOTE Imbalanced classification report](./Images/SMOTE_imbalanced_classification_report.PNG)

**ClusterCentroids**
- An accuracy score for the model was calculated: 0.8325
- A confusion matrix has been generated <br>
![ClusterCentroids Confusion Matrix](./Images/ClusterCentroid_confusion_matrix.png)

- An imbalanced classification report has been generated<br>
![ClusterCentroids imbalanced classification report](./Images/ClusterCentroid_imballanced_classification_report.png)

### Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* The combinatorial SMOTEENN algorithm had the following:

**SMOTEENN**
- An accuracy score for the model was calculated: 0.8389
- A confusion matrix has been generated <br>
![SMOTEEN Confusion Matrix](./Images/SMPT_confusion_matrix.png)

- An imbalanced classification report has been generated<br>
![SMOTEEN imbalanced classification report](./Images/SMPT_classification_report.png)

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
* The BalancedRandomForestClassifier algorithm does the following:
- An accuracy score for the model was calculated: 0.759
- A confusion matrix has been generated <br>
![BalanceRandomForestClassifier Confusion Matrix](./Images/BalancedRandomForestClassifier_confusion_matrix.png)
- An imbalanced classification report has been generated <br>
![BalancedRandomForestClassifier imbalanced classification report](./Images/BalancedRandomForestClassifier_classification_report.png)
- The features are sorted in descending order by feature importance

* The EasyEnsembleClassifier algorithm does the following:
- An accuracy score for the model was calculated: 0.9319
- A confusion matrix has been generated <br>
![EasyEnsembleClassifier Confusion Matrix](./Images/EasyEnsembleClassifier_confusion_matrix.png)
- An imbalanced classification report has been generated <br>
![EasyEnsembleClassifier imbalanced classification report](./Images/Easy_Ensemble_Clssification_report.PNG)
- The features are sorted in descending order by feature importance