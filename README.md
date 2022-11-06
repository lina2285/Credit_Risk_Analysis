# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to gauge credit risk through building a supervised machine learning model to help Jill have a more clear understanding of risk before meeting with potential investors. In this model the loan status is being analyzed as "high-sisk" or "low-risk" classes. Unfortunatelly, these classes are not balanced as the low risk loans outnumber the high-risk loans, consequently, we are using the imbalanced-learn library. For this we used RandomOverSample and SMOTE, ClusterCentroids, SMOTEENN, BlancedRandomForestClassifier and EasyEsembleClassifier. 


## Results

### Oversampling

![Oversampling](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/OVERSAMPLING_ACTUAL_RISK_REPORT.png)

![Smote](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/SMOTE_ACTUAL_RISK_REPORT.png)

![Undersampling](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/UNDERSAMPLING_ACTUAL_RISK_REPORT.png)

![Smoteenn](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/SMOTEENN_ACTUAL_RISK_REPORT.png)

![Forest Classifier](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/RANDON_FOREST.png)

![EasyEnsembleAdaboost](https://github.com/lina2285/Credit_Risk_Analysis/blob/main/ENSEBLE_ADABOOST.png)

## Summary
Based on the results, the EasyEnsembleClassifier proves to be the most effective with an accuracy score above 90%. Given that this gives that best precision, Jill can use this analysis with confidence that the projected risk is being planned for accurately. 
