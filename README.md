# Sentiment Analysis on Mental Health Text Data

## Project Overview

This project focuses on performing sentiment analysis on mental health-related text data using various deep learning models. The goal is to classify text entries based on their emotional tone, leveraging TensorFlow and Keras for model development. Models implemented include Dense Neural Networks, Convolutional Neural Networks (CNN), and Long Short-Term Memory Networks (LSTM).

## Key Features

Multi-model Analysis: Experimentation with Dense, CNN, and LSTM models for sentiment classification.

Visualization and Evaluation: Performance is evaluated using confusion matrices and classification reports.

Comprehensive Preprocessing: Utilizes Pandas and NumPy for data processing and Seaborn/Matplotlib for visualization.

Sklearn Integration: Used for model evaluation and generating performance metrics.

## Tools and Technologies

TensorFlow/Keras - Model development

Pandas & NumPy - Data processing

Matplotlib & Seaborn - Visualization

Sklearn - Model evaluation and classification report

## Dataset

The dataset consists of mental health journal entries labeled with emotions. It contains textual data that requires preprocessing, tokenization, and vectorization before feeding into neural networks.

## Installation

Install required packages:

pip install tensorflow pandas numpy matplotlib seaborn scikit-learn

How to Run

Load the dataset (mental_health.csv).

Preprocess the data, including tokenization and padding.

Train the models by running the Python script:

python sentiment_analysis_ml.py

Evaluate model performance through confusion matrices and accuracy plots.

## Results

The models are trained and validated over multiple epochs.

Accuracy and performance of Dense, CNN, and LSTM models are compared.

Confusion matrices visualize the classification performance.


