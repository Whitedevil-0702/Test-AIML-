# Lesson 03 — Evaluation, Overfitting, and Data Leakage

## Training, validation, and test

- **Training set:** used to fit model parameters.
- **Validation set:** used to compare choices or tune settings.
- **Test set:** held back for a final, relatively unbiased estimate after decisions are made.

For small datasets, cross-validation can help estimate variability. The split strategy must match the real-world setting; time-dependent data often requires a chronological split.

## Overfitting

Overfitting occurs when a model captures quirks of the training data that do not generalize. Compare training performance with validation/test performance and prefer the simplest model that meets the need.

## Data leakage

Leakage occurs when information unavailable at the intended prediction time influences training or evaluation. Examples include using future data to predict the past or preprocessing the entire dataset before splitting when that step learns information from the data.

## Activity

Write a short evaluation plan before training:
- What data is held out?
- Which metric will be used and why?
- What baseline is appropriate?
- What leakage risks exist?
- What failure cases should be inspected?

## Check your understanding

1. Why should test data not be used repeatedly to tune a model?
2. Give an example of leakage.
3. What would you do if a model's training score is high but its test score is low?
