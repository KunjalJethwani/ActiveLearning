# Emotion Classification Using Active Learning

## Project Overview
This project focuses on emotion classification using the IEMOCAP dataset. The goal is to build a robust model for identifying emotions in text using an Active Learning framework with Uncertainty Sampling. The project implements advanced deep learning techniques to handle textual data efficiently.

## Dataset
- **Name**: IEMOCAP (https://sail.usc.edu/iemocap/)
- **Description**: A dataset containing multimodal emotion recognition data.
- **Usage**: Text transcriptions were extracted and used for this project.

## Model Architecture
- **Text Vectorization**: Converts text to integer sequences.
- **Embedding Layer**: Maps tokens to 200-dimensional dense vectors.
- **Bidirectional LSTM**: Captures sequential relationships with 64 units.
- **Global Max Pooling**: Extracts dominant features across sequences.
- **Dense Layers**: Includes a hidden layer (64 units, ReLU activation) and an output layer (8 units, softmax activation).

## Active Learning Framework
- **Uncertainty Sampling**: Selects samples with the highest uncertainty for manual labeling.
- **Objective**: Minimizes labeling effort while improving model performance.

## Requirements
- Python 3.8+
- TensorFlow
- Keras
- NumPy
- pandas
- scikit-learn
- regex
- seaborn


