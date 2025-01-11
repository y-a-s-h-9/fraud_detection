
# Credit Card Fraud Detection System

## Overview

This project implements a machine learning-based system to detect fraudulent credit card transactions. It uses a Random Forest classifier to classify transactions as legitimate or fraudulent. The system is designed for scalability and can be integrated into real-world financial systems.

## Features

- **Data Handling**:
  - Preprocesses raw transaction data (handles missing values and encodes categorical features).
  - Extracts meaningful features like transaction frequency for better model performance.
- **Machine Learning**:
  - Implements a Random Forest classifier for robust fraud detection.
  - Standardizes features to improve model accuracy.
- **Performance Evaluation**:
  - Outputs detailed classification reports (precision, recall, F1-score).
  - Computes the ROC-AUC score to measure model performance.
- **Deployment**:
  - Saves the trained model for real-time predictions using `joblib`.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
3. Run the script:
   ```bash
   python fraud_detection.py
## Usage

### Data Input:
- Ensure the dataset is a CSV file named credit_card_transactions.csv.
- If no dataset is provided, the script generates a sample dataset for demonstration.
### Run the Detection System:
- The script preprocesses the data, trains a Random Forest classifier, and evaluates the model.
### Model Output:
- The trained model is saved as fraud_detection_model.pkl for deployment.
  
## Example Output

### Classification Report:

               precision    recall  f1-score   support

           0       0.95      0.98      0.96      1500
           1       0.88      0.78      0.83       500

    accuracy                           0.94      2000
   macro avg       0.91      0.88      0.89      2000
weighted avg       0.94      0.94      0.94      2000
ROC-AUC Score: 0.93

## Key Insights:
- Precision: Indicates how many predicted fraudulent transactions are correct.
- Recall: Reflects how well the model identifies all actual fraud cases.
- ROC-AUC Score: A value of 0.93 shows excellent performance in distinguishing between legitimate and fraudulent transactions.
  
## Project Structure

- fraud_detection.py: Main script for loading data, training, and evaluating the model.
- requirements.txt: List of required Python libraries.
- fraud_detection_model.pkl: Trained model for deployment.

## Technologies Used

### Programming Language: Python
### Libraries:
- pandas: Data manipulation.
- scikit-learn: Machine learning and preprocessing.
- joblib: Model serialization.




## Output

<img width="1440" alt="Screenshot 2025-01-11 at 21 48 39" src="https://github.com/user-attachments/assets/c0cbef9b-0671-49bf-8096-d664e265996e" />


