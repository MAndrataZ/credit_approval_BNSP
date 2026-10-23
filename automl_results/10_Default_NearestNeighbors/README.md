# Summary of 10_Default_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 5
- **weights**: uniform
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
accuracy

## Training time

3.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.436189 |       nan   |
| auc       | 0.957207 |       nan   |
| f1        | 0.960352 |         0.2 |
| accuracy  | 0.941176 |         0.2 |
| precision | 0.98     |         0.6 |
| recall    | 0.990991 |         0   |
| mcc       | 0.849732 |         0.2 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.436189 |       nan   |
| auc       | 0.957207 |       nan   |
| f1        | 0.960352 |         0.2 |
| accuracy  | 0.941176 |         0.2 |
| precision | 0.939655 |         0.2 |
| recall    | 0.981982 |         0.2 |
| mcc       | 0.849732 |         0.2 |


## Confusion matrix (at threshold=0.2)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               35 |                7 |
| Labeled as 1 |                2 |              109 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
