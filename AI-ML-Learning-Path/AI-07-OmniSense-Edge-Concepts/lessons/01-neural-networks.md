# Lesson 1 — Neural Networks: Layers, Weights, and Activations

**Resource:** *3Blue1Brown – But What Is a Neural Network?* (about 19 minutes; URL needs verification).

## Goal

Build an intuitive explanation of how a neural network transforms input numbers into an output.

## Core idea

A neural network passes numerical values through layers. Connections have **weights**, units can have **biases**, and activation functions introduce non-linearity. Without useful nonlinear behavior, stacking layers would not provide the expressive power usually expected from a deep network.

For OmniSense Edge, the input might eventually be features extracted from a sound recording or an image. A model could produce a score or classification, but its output is only useful if the data and evaluation process support it.

## Terms to know

- **Input:** values presented to the model.
- **Weight:** a learned multiplier controlling a connection's influence.
- **Bias:** a learned offset.
- **Activation function:** a function such as ReLU or sigmoid applied to a unit's value.
- **Layer:** a group of computational units.
- **Prediction:** the model's output for an input.

## Explain it yourself

Draw a small network with an input layer, one hidden layer, and an output. Label the weights and biases. Explain why an activation function is used without relying on the phrase “the AI learns.”

## Check your understanding

1. What does a weight change?
2. What is the role of a bias?
3. Why are nonlinear activation functions useful?
4. What would you need to define before deciding whether a model's output is correct?

## Deliverable

Submit one labeled diagram and a 150–250 word explanation. Include one example of possible inputs and outputs for machine monitoring, clearly labelled as a hypothetical example.
