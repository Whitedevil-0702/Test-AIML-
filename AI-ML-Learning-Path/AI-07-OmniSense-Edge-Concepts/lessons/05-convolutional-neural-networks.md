# Lesson 5 — Convolutional Neural Networks (CNNs)

**Resource:** *A Visual Guide to Convolutional Neural Networks (CNNs)* (about 12 minutes; exact source URL needs verification).

## Goal

Explain how convolutional filters can detect local patterns in images.

## Core idea

A convolutional layer applies learned filters, often called **kernels**, across local regions of an input. Early layers may respond to simple visual patterns; deeper layers can combine patterns into more complex representations. This is a useful intuition, not a guarantee that every layer has a human-interpretable role.

## Project connection

For visual inspection, an image model might be trained to classify a component or detect a visible defect. Image quality, camera position, lighting, labeling consistency, and the range of defect examples strongly affect results.

## Check your understanding

1. What does a convolutional kernel do?
2. Why process local regions instead of treating every pixel independently?
3. Why can a model trained under one lighting setup fail under another?
4. What is the difference between classification and object detection?

## Mini-lab

Use a small, appropriately licensed image dataset or synthetic images to visualize a convolution operation. If you train a model, split the data before tuning and report the evaluation setup.

## Deliverable

Submit a diagram of a kernel sliding over an image, a short explanation, and a note describing the data needed to evaluate a visual-inspection model responsibly.
