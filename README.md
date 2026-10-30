# Binary Classification Using Single-Layer Perceptron

## Project Overview
This project implements a Single-Layer Perceptron (SLP) from scratch using Python and NumPy for binary classification.

The model uses the Banknote Authentication Dataset to classify banknotes into two categories based on four numerical features.

## Dataset Information
- Dataset Name: Banknote Authentication
- Source: UCI Machine Learning Repository
- Total Instances: 1,372
- Input Features: 4
- Output Classes: 2

## Dataset Source
https://archive.ics.uci.edu/dataset/267/banknote+authentication

## Technologies Used
- Python
- NumPy
- Pandas
- Jupyter Notebook

## Implementation Steps
1. Dataset loading
2. Data preprocessing
3. Missing value checking
4. Training and testing split (80/20)
5. Feature standardization
6. Single-Layer Perceptron implementation from scratch
7. Model training and testing
8. Performance evaluation

## Model Performance

| Metric | Result |
|---|---:|
| Accuracy | 98.55% |
| Precision | 96.83% |
| Recall | 100.00% |
| F1 Score | 98.39% |

## Confusion Matrix

| Actual / Predicted | Class 0 | Class 1 |
|---|---:|---:|
| Class 0 | 149 | 4 |
| Class 1 | 0 | 122 |

## Project Files
- Binary_Classification_SLP.ipynb – Complete Python code and output.
- banknote_authentication.csv – Dataset.
- README.md – Project documentation.

## Conclusion
The Single-Layer Perceptron successfully performed binary classification with 98.55% accuracy. The model was implemented from scratch without using any prebuilt machine learning classifiers.
