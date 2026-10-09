# Lesson 2 — Loss, Gradient Descent, and Backpropagation

**Resource:** *3Blue1Brown – Gradient Descent & Backpropagation* (about 15 minutes; URL needs verification).

## Goal

Explain how a model's parameters can be adjusted to reduce prediction error during training.

## Core idea

A **loss function** measures how poorly a model's prediction matches the training target under a chosen objective. **Gradient descent** uses gradient information to update parameters in a direction intended to reduce the loss. **Backpropagation** efficiently computes gradients through the network using the chain rule.

These are related but distinct: loss defines the objective, backpropagation calculates gradients, and the optimizer uses those gradients to update parameters.

## Project connection

If a training dataset contains examples with labels, a model can be trained against an appropriate loss. For an autoencoder trained on normal sound examples, the objective may instead measure how well the model reconstructs its input.

## Check your understanding

1. Why is a loss function needed?
2. What information does a gradient provide?
3. How is backpropagation different from gradient descent?
4. What might happen if the learning rate is too large or too small?

## Mini-experiment

Use a simple plotted function or a beginner notebook to visualize iterative updates toward a minimum. Change the learning rate and record how the update path changes. Do not claim that a toy function proves a model will train well on real machine data.

## Deliverable

Submit a diagram connecting **prediction → loss → gradients → parameter update**, plus a short note describing one limitation of optimizing training loss.
