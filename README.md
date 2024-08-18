# Fake-News-Detection-Model

## Overview

This project involves building and evaluating machine learning models to detect fake news. The goal is to classify news articles as either "Fake News" or "Not Fake News" using various classifiers and deep learning techniques.

## Project Structure

- `data/`: Directory containing datasets used for training and evaluation.
- `notebook.ipynb`: Jupyter notebook with code for data exploration, preprocessing, model training, and evaluation.
- `requirements.txt`: List of Python packages required to run the project.
- `README.md`: This file.

## Models Used

1. **Ensemble Model**: Combines predictions from multiple classifiers:
   - Logistic Regression
   - Decision Tree Classifier
   - Gradient Boosting Classifier
   - Random Forest Classifier

2. **LSTM Model**: A Long Short-Term Memory network used for text classification.

## Performance Metrics

### Ensemble Model
- **Logistic Regression**:
  - Precision: 0.99
  - Recall: 0.99
  - F1-Score: 0.99

- **Decision Tree Classifier**:
  - Precision: 0.99
  - Recall: 0.99
  - F1-Score: 0.99

- **Gradient Boosting Classifier**:
  - Precision: 1.00
  - Recall: 0.99
  - F1-Score: 0.99

- **Random Forest Classifier**:
  - Precision: 0.99
  - Recall: 0.99
  - F1-Score: 0.99

### LSTM Model
- **LSTM**:
  - Precision: 0.98
  - Recall: 0.98
  - F1-Score: 0.98

## Methodology

1. **Data Preprocessing**: Tokenization, padding, and vectorization of text data.
2. **Model Training**:
   - **Ensemble Model**: Training multiple classifiers and combining their predictions.
   - **LSTM Model**: Training a Long Short-Term Memory network for sequence classification.
3. **Evaluation**: Metrics including precision, recall, and F1-score were used to evaluate the performance of the models.

## Manual Testing

The models can be manually tested using the provided code to enter news articles and get predictions. See `notebook.ipynb` for details on how to test the models.

## Requirements

To run this project, install the necessary Python packages:

```bash
pip install -r requirements.txt
