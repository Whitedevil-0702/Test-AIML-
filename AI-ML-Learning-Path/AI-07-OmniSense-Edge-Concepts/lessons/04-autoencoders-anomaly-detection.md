# Lesson 4 — Autoencoders for Anomaly Detection

**Resource:** *Autoencoders – Explained Animation* (about 8 minutes; exact source URL needs verification).

## Goal

Explain the encoder–bottleneck–decoder architecture and the idea of using reconstruction error as an anomaly signal.

## Core idea

An autoencoder learns to reconstruct an input. The **encoder** maps the input to a compact representation, often called the latent representation or bottleneck. The **decoder** uses that representation to reconstruct the input.

A common anomaly-detection approach is to train an autoencoder on examples representing normal behavior, then examine reconstruction error on new examples. If unusual inputs are reconstructed poorly, their error may be higher. This is a hypothesis to validate, not a guarantee: some anomalies may reconstruct well, and normal variation can also produce high error.

## Project connection

For machine acoustics, the input could be a consistent audio feature representation. A candidate anomaly score might be reconstruction error, with a threshold selected using validation data.

## Important evaluation questions

- What exactly counts as “normal”?
- Does the training set cover normal operating speeds, loads, and environments?
- How will the threshold be chosen?
- What are the false-positive and false-negative rates?
- How will model drift or new machine states be handled?

## Mini-lab

Use a toy dataset to train an autoencoder, plot reconstruction errors for training and held-out examples, and test a threshold. If no labeled anomalies are available, state that the experiment cannot establish real-world detection performance.

## Deliverable

Submit an architecture diagram, a plot of reconstruction errors, the threshold rationale, and a short failure-analysis note.
