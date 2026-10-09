# Lesson 02 — Regression, Classification, and Clustering

## Regression

Regression predicts a numeric quantity, such as delivery time or house price. Possible metrics include mean absolute error (MAE) and root mean squared error (RMSE). Metric choice depends on how errors should be interpreted.

## Classification

Classification predicts a category, such as spam/not spam. Accuracy is the fraction of correct predictions, but it can mislead when classes are imbalanced. Precision, recall, F1, and a confusion matrix provide additional information.

## Clustering

Clustering groups examples by similarity without a supplied target label. A cluster is not automatically a meaningful real-world category; the team must inspect and validate the result.

## Activity

For each problem, select a task type and justify it:
- Predict next week's demand.
- Flag a message as spam or legitimate.
- Group similar music listeners when no groups are supplied.

## Common mistakes

- Using accuracy for every classification problem.
- Treating clusters as ground truth.
- Comparing models with different test sets without explaining the difference.
- Reporting a metric without describing what a mistake costs.

## Next step

Read [Lesson 03](03-evaluation-and-leakage.md).
