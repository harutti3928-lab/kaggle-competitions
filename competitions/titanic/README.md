# Titanic — Machine Learning from Disaster

## Competition overview

Predict whether each passenger in the test set survived the Titanic disaster.

## Dataset description

| File | Contents |
| --- | --- |
| `train.csv` | Passenger features and the binary `Survived` target |
| `test.csv` | Passenger features with no survival labels |
| `gender_submission.csv` | Example predictions and the required CSV format |

Features include passenger class, sex, age, family counts, fare, cabin, and embarkation port. Join the competition, then save the CSVs in the local `data/` directory. Save any future prediction CSVs in `submissions/`.

## Evaluation metric

Accuracy is the fraction of passengers whose predicted survival label matches the actual outcome. The submission columns are `PassengerId` and `Survived`.

## Planned approaches

1. Inspect missing values, feature distributions, and survival rates.
2. Set up a stratified validation split and compare a majority-class baseline with logistic regression.
3. Compare tree-based models using consistent validation splits. Fit preprocessing on training folds only.

## Experiment results

| Date | Model | Validation setup | Validation accuracy | Kaggle accuracy | Notes |
| --- | --- | --- | --- | --- | --- |
| | | | | | |

## Lessons learned

-

## Official competition

[Titanic on Kaggle](https://www.kaggle.com/competitions/titanic)
