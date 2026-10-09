# Lesson 3 — Audio Features and Spectrograms

**Resource:** *Valerio Velardo – Audio Features & Spectrograms* (about 15 minutes; URL needs verification).

## Goal

Understand why sound can be represented as a time-frequency image-like array for analysis.

## Core idea

A recorded sound is a signal that changes over time. A spectrogram represents how signal energy is distributed across time and frequency. A Mel spectrogram uses a frequency scale designed to reflect aspects of human auditory perception.

This representation can make patterns in a machine's acoustic behavior easier for a model to process. It does not automatically make the model accurate: microphone placement, background noise, operating speed, and recording conditions can all affect the signal.

## Project connection

A conceptual pipeline might be:

1. Capture an audio segment.
2. Apply consistent preprocessing.
3. Calculate a spectrogram or Mel spectrogram.
4. Feed the representation to a suitable model.
5. Evaluate its output against held-out recordings and known conditions.

This is a conceptual pipeline, not a validated production design.

## Check your understanding

1. What are the two axes of a spectrogram?
2. What information can be lost or altered during preprocessing?
3. Why should training and evaluation recordings reflect realistic operating conditions?
4. Why might the same machine sound different across recording setups?

## Lab preview

Create or load a short audio clip, plot its waveform, and plot a spectrogram. Document the sample rate, clip duration, and preprocessing choices.

## Deliverable

Submit the plots, code/notebook, a description of visible patterns, and at least two limitations of the experiment.
