# Urdu Audio Classification with Machine Learning

## Overview

This project implements a voice-activated assistant with machine learning capabilities designed to understand and respond in the Urdu language. The system uses Mel-frequency cepstral coefficients (MFCC) features for audio classification. Various machine learning models, including K-Nearest Neighbors (KNN), Decision Tree, Linear Support Vector Classifier (LinearSVC), Logistic Regression, and Random Forest, have been implemented.

## Data Processing and Model Training

The `MLcode.py` script is responsible for processing audio data, extracting MFCC features, and training the machine learning models. The data is organized by labels.

## Flask Backend

The Flask application (`app.py`) provides an API for serving the trained models. It includes the following endpoints:

- `/predict` - POST endpoint for making predictions on audio samples.

To start the Flask application, run:

```bash
python app.py


```

### Data Preparation:

Organize your audio data in the data/ directory with subdirectories with label names
