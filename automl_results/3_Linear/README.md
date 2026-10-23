# Summary of 3_Linear

[<< Go back](../README.md)


## Logistic Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
accuracy

## Training time

20.1 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.18066  | nan          |
| auc       | 0.972758 | nan          |
| f1        | 0.973214 |   0.469553   |
| accuracy  | 0.960784 |   0.469553   |
| precision | 0.988372 |   0.930422   |
| recall    | 1        |   0.00566418 |
| mcc       | 0.901544 |   0.521902   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.18066  |  nan        |
| auc       | 0.972758 |  nan        |
| f1        | 0.973214 |    0.469553 |
| accuracy  | 0.960784 |    0.469553 |
| precision | 0.964602 |    0.469553 |
| recall    | 0.981982 |    0.469553 |
| mcc       | 0.900565 |    0.469553 |


## Confusion matrix (at threshold=0.469553)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               38 |                4 |
| Labeled as 1 |                2 |              109 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                |    Learner_1 |
|:-----------------------|-------------:|
| intercept              |  3.02496     |
| tunggakan_pokok        |  2.71554     |
| tunggakan_bunga        |  1.32779     |
| bi_gol_penjamin        |  1.11784     |
| col                    |  1.08104     |
| umur                   |  0.0537526   |
| saldo_nominatif        |  0.000665375 |
| jml_angsuran_per_bulan | -0.13982     |
| jml_pinjaman           | -1.43455     |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
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



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions for class 0 (Fold 1)
![SHAP worst decisions class 0 from Fold 1](learner_fold_0_shap_class_0_worst_decisions.png)
### Top-10 Best decisions for class 0 (Fold 1)
![SHAP best decisions class 0 from Fold 1](learner_fold_0_shap_class_0_best_decisions.png)
### Top-10 Worst decisions for class 1 (Fold 1)
![SHAP worst decisions class 1 from Fold 1](learner_fold_0_shap_class_1_worst_decisions.png)
### Top-10 Best decisions for class 1 (Fold 1)
![SHAP best decisions class 1 from Fold 1](learner_fold_0_shap_class_1_best_decisions.png)

[<< Go back](../README.md)
