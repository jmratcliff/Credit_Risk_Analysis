# Credit Risk Analysis
 *Technical analysis of credit risk utilizing Python and machine learning*
 
## Overview
Evaluate credit risk using six different machine learning models.  Credit risk is an unbalanced classification problem in that the population of performing loans typically greatly outnumber the population of non-performing (delinquent) loans.  Different techniques were used to train and evaluate different models with unbalanced classes. Credit card data from LendingClub with 68k+ records were used to evaluate the following six models:
* RandomOverSampler
* SMOTE
* ClusterCentroids
* SMOTEENN
* BalancedRandomForestClassifier
* EasyEnsembleClassifier

Models were run and evaluated by looking at the balanced accuracy score, confusion matrix, and imbalanced classification report for each model.

## Results
*Terms and concepts first defined, followed by the results for each model

### Measures
**Balanced Accuracy Score** - The difference between the predicted values and the actual values. This measure is problematic when evaluating imbalanced classes because it is important to accurately predict the smaller class.

**Confusion Matrix** - Breaks the number of records into the predicted values and actual values to identify: true positives, true negatives, false positives, and false negatives as seen below.
![confusion matrix](/images/cm.png)

**Imbalanced Classification Report** - 
    
***Precision*** - How reliable a positive classification is (TP/(TP+FP)

***Sensitivity/Recall*** - Measure of ability to identify all positive classifications (TP/(TP+FN)

***F1 Score*** - aka 'Harmonic Mean' summary statistic of both precision and sensitivity (2(Precision*Sensitivity)/(Precision+Sensitivity). A very low F1 score indicates an imbalance between Precision and Sensitivity.

### Model Results
**RandomOverSampler** - 

*Balanced Accuracy Score*

![ros_bac](/images/ROS_bac.png)

*Confusion Matrix*

![ros_cm](/images/ROS_cm.png)

*Imbalanced Classification Report*

![ros_icr](/images/ROS_icr.png)

**SMOTE** - 

*Balanced Accuracy Score*

![smote_bac](/images/SMOTE_bac.png)

*Confusion Matrix*

![smote_cm](/images/SMOTE_cm.png)

*Imbalanced Classification Report*

![smote_icr](/images/SMOTE_icr.png)

**ClusterCentroids** - 

*Balanced Accuracy Score*

![cc_bac](/images/CC_bac.png)

*Confusion Matrix*

![cc_cm](/images/CC_cm.png)

*Imbalanced Classification Report*

![cc_icr](/images/CC_icr.png)

**SMOTEENN** - 

*Balanced Accuracy Score*

![smoteenn_bac](/images/SMOTEENN_bac.png)

*Confusion Matrix*

![smoteenn_cm](/images/SMOTEENN_cm.png)

*Imbalanced Classification Report*

![smoteenn_icr](/images/SMOTEENN_icr.png)

**BalancedRandomForestClassifier** - 

*Balanced Accuracy Score*

![brfc_bac](/images/BRFC_bac.png)

*Confusion Matrix*

![brfc_cm](/images/BRFC_cm.png)

*Imbalanced Classification Report*

![brfc_icr](/images/BRFC_icr.png)

**EasyEnsembleClassifier** - 

*Balanced Accuracy Score*

![eec_bac](/images/EEC_bac.png)

*Confusion Matrix*

![eec_cm](/images/EEC_cm.png)

*Imbalanced Classification Report*

![eec_icr](/images/EEC_icr.png)


## Summary
