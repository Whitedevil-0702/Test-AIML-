# Lesson 01 — From Data to Model

## Intuition

A model is a learned mapping from inputs to outputs. During training, an algorithm uses examples to adjust the model so that its predictions fit the training objective. The result is not a guarantee of truth; it is a learned pattern that must be tested.

## Vocabulary

- **Example/row:** one observation.
- **Feature:** an input field used by the model.
- **Target/label:** the output to predict.
- **Training:** fitting model parameters from training data.
- **Inference:** using a fitted model to produce a prediction.
- **Generalization:** performance on new cases beyond the training examples.

## A simple pipeline

Problem → dataset → split → baseline → train → evaluate → inspect errors → communicate.

## Activity

For a house-price dataset, identify three plausible features, the target, one feature that might be unavailable at prediction time, and one source of bias.

## Check your understanding

1. What is the difference between a feature and a target?
2. Why can a model perform well on training data but poorly on new data?
3. Why is a simple baseline useful?

## Next step

Read [Lesson 02](02-regression-classification.md).
