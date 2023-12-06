# Fake News Detection Project

## Overview

The Fake News Detection project aims to build a classifier using LSTM (Long Short-Term Memory) to identify potentially unreliable news articles. The project utilizes a dataset ('train.csv') containing information about news articles, including title, author, text, and a label indicating the article's reliability.

## Key Features

- **LSTM Model:** The core of the project is a deep learning model based on LSTM architecture, known for its effectiveness in sequence processing tasks.

- **Training and Testing:** The model is trained on a labeled dataset and evaluated on a separate test set to assess its generalization performance.

- **Evaluation Metrics:** Key metrics such as accuracy, confusion matrix, and ROC AUC are used to evaluate the model's performance.

## Usage

1. **Dataset:** Ensure the 'train.csv' dataset is available for training and testing.

2. **Model Training:** Execute the notebook or script to train the LSTM model on the provided dataset.

3. **Model Evaluation:** Evaluate the model using various metrics, including accuracy, confusion matrix, and ROC AUC.

4. **Visualizations:** Explore visualizations such as ROC curves and confusion matrices for a comprehensive understanding of the model's behavior.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Results

- **Training Accuracy:** 99.99%
- **Test Accuracy:** 91.45%
- **ROC AUC:** 0.91

## Conclusion

The Fake News Detection model demonstrates strong discriminatory power, effectively distinguishing between reliable and unreliable news articles. Regular evaluations and potential fine-tuning are recommended to maintain the model's relevance and accuracy over time.

Feel free to explore the notebook for a detailed walkthrough of the project and its outcomes.

**Note:** Adjustments to the hyperparameters and model architecture can be made based on specific use case requirements.

