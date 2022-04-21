# Credit_Risk_Analysis

## Overview:

The purpose of this analysis was to examine credit risk using machine learning algorithms.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampling:
 - Captured effectively all low risk samples, but almost no high risk samples.
 - Has reasonable recall scores for both high risk and low risk.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/random_oversampling.PNG)

### SMOTE Oversampling
 - Captured effectively all low risk samples, but almost no high risk samples.
 - Slightly lower recall for high risk, slightly higher recall for low risk.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/smote_oversampling.PNG)

### Undersampling
 - Captured effectively all low risk samples, but almost no high risk samples.
 - Far lower recall for low risk than oversampling, slightly lower recall for high risk.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/undersampling.PNG)

### SMOTEENN
 - Captured effectively all low risk samples, but almost no high risk samples.
 - Lower recall for low risk than other models, comparable precision for high risk.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/smoteenn.PNG)

### Random Forest
 - Very high precision scores for both results.
 - Poor recall for high risk, very high recall for low risk.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/random_forest.PNG)

### Ensemble AdaBoost
 - High scores across the board.  Excellent accuracy, precision, and recall.

![img](https://github.com/kchavez05/Credit_Risk_Analysis/blob/main/Images/AdaBoost.PNG)

## Summary:

The clear winner in our analysis is the Ensemble AdaBoost.  It was the only model that got high scores in all categories.  It does take some time to run, so considerations will need to be made with regards to resources, but based on our results it would be well worth it.
