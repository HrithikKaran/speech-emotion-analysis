# speech-emotion-analysis
Speech Emotion Recognition Project

This repository contains speech and emotion analysis, focusing on building a deep learning model to classify emotions in speech using the Toronto Emotional Speech Set (TESS) dataset.

Project Overview
The goal of this project is to develop a model that accurately identifies different emotions such as anger, happiness, and sadness from audio recordings.

Technologies Used
Librosa: For audio processing and feature extraction.
Seaborn & Matplotlib: For data visualization.
Keras: For building and training the neural network.
Scikit-learn: For model evaluation.
Key Steps
Dataset Preparation: Downloaded and organized the TESS dataset.
Data Exploration: Visualized waveforms and spectrograms to understand audio characteristics.
Feature Extraction: Extracted Mel-frequency cepstral coefficients (MFCCs) from audio files.
Model Building: Created a model with LSTM, dropout, and dense layers to improve learning and prevent overfitting.
Training and Evaluation: Trained the model and evaluated its performance using confusion matrices and classification reports, visualized with heatmaps.
Outcome
This project provided valuable insights into the process of building and evaluating a neural network for speech emotion recognition, highlighting the importance of data preprocessing, model selection, and performance evaluation.
