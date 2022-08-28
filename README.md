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


## Summary
