# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model              |   Weight |
|:-------------------|---------:|
| 6_Default_CatBoost |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.100003 | nan          |
| auc       | 0.982304 | nan          |
| f1        | 0.991071 |   0.491854   |
| accuracy  | 0.986928 |   0.491854   |
| precision | 0.990909 |   0.623877   |
| recall    | 1        |   0.00815147 |
| mcc       | 0.967225 |   0.491854   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.100003 |  nan        |
| auc       | 0.982304 |  nan        |
| f1        | 0.991071 |    0.491854 |
| accuracy  | 0.986928 |    0.491854 |
| precision | 0.982301 |    0.491854 |
| recall    | 1        |    0.491854 |
| mcc       | 0.967225 |    0.491854 |


## Confusion matrix (at threshold=0.491854)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               40 |                2 |
| Labeled as 1 |                0 |              111 |

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
