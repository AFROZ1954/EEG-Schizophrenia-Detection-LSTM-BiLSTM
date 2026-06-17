# EEG-Based Schizophrenia Detection using LSTM and BiLSTM

This project focuses on schizophrenia detection using EEG signals and deep learning models.

In the previous machine learning pipeline, EEG signals were processed using handcrafted features, PCA, SVM tuning, classifier comparison, brain-region analysis, and top-channel analysis.

In this project, the same EEG dataset is used for deep learning-based classification using LSTM and BiLSTM models. Since EEG is a time-series biomedical signal, recurrent neural networks are suitable for learning temporal patterns directly from EEG epochs.

## Dataset

The dataset contains EEG recordings from schizophrenia patients and healthy control subjects.

- Total subjects: 84
- EEG channels: 16
- Sampling frequency: 128 Hz
- Duration per subject: 60 seconds
- Samples per channel: 7680

After epoching:

- Window length: 5 seconds
- Samples per epoch: 640
- Total epochs: 1008
- Input shape: 1008 × 16 × 640

## Models Used

- LSTM
- BiLSTM

## Aim

The aim of this project is to compare LSTM and BiLSTM models for EEG-based schizophrenia classification.
