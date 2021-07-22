# Summary of 5_Default_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
- **eval_metric_name**: logloss
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

6.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.346198 | nan         |
| auc       | 0.888408 | nan         |
| f1        | 0.658454 |   0.31545   |
| accuracy  | 0.847338 |   0.404534  |
| precision | 0.986755 |   0.831597  |
| recall    | 1        |   0.0316256 |
| mcc       | 0.555361 |   0.404534  |


## Confusion matrix (at threshold=0.404534)
|                  |   Predicted as <=50K |   Predicted as >50K |
|:-----------------|---------------------:|--------------------:|
| Labeled as <=50K |                 4338 |                 289 |
| Labeled as >50K  |                  643 |                 835 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)



[<< Go back](../README.md)
