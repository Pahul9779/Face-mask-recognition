# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning. The goal is to build a reliable model that can identify fraudulent activities while minimizing false positives. This project addresses the real-world challenge of class imbalance in fraud detection datasets.

## Features
- **Data Preprocessing**: 
  - Handled missing values.
  - Normalized transaction data for consistent scaling.
- **Exploratory Data Analysis (EDA)**:
  - Visualized transaction distributions.
  - Identified key patterns and outliers.
- **Class Imbalance Handling**:
  - Used oversampling (SMOTE) and undersampling techniques to balance the dataset.
- **Model Development**:
  - Trained and tested multiple machine learning models.
  - Performed hyperparameter tuning for optimal performance.
- **Evaluation Metrics**:
  - Measured performance using accuracy, precision, recall, F1-score, and ROC-AUC.

## Dataset
The dataset contains anonymized features and includes:
- **Time**: Time elapsed since the first transaction.
- **V1 to V28**: Principal components derived from PCA.
- **Amount**: Transaction amount in currency units.
- **Class**: Target variable (0 = legitimate, 1 = fraudulent).

**Dataset Source:**  
Refer to the `Credit_Card_Fraud_Detection.ipynb` file for dataset details and preprocessing steps.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries Used**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Imbalanced-learn
- **Notebook Environment**: Jupyter Notebook

## Project Files
- `Credit_Card_Fraud_Detection.ipynb`: Jupyter Notebook containing all steps of the project, including data preprocessing, EDA, model training, and evaluation.
- `README.md`: Overview of the project.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Credit_Card_Fraud_Detection.git

## Results

| Metric         | Value  |
|----------------|--------|
| **Accuracy**   | 99%    |
| **Precision**  | 94%    |
| **Recall**     | 90%    |
| **F1-Score**   | 92%    |
| **ROC-AUC**    | 97%    |

### Model Performance Insights
- The model demonstrates high **accuracy** and **ROC-AUC**, indicating its effectiveness in differentiating between fraudulent and legitimate transactions.
- **Precision** and **Recall** are balanced, ensuring that false positives and false negatives are minimized.

