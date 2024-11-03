# Credit Card Fraud Detection

## Project Overview
This project focuses on building a machine learning model to detect fraudulent credit card transactions. Using anonymized transaction data, the model identifies which transactions are likely fraudulent. This classification helps in preventing fraud and protecting financial institutions and customers.

## Features
- **Data Preprocessing**: Importing and cleaning the dataset.
- **Exploratory Data Analysis**: Analyzing data distribution and features.
- **Model Training**: Using logistic regression for binary classification.
- **Evaluation**: Measuring model performance through metrics like accuracy and confusion matrix.

## Technologies Used
- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook

## Installation and Usage
1. Clone the repository:
   ```bash
      git clone https://github.com/parthdave333/credit-card-fraud-detection.git

2. Open the Jupyter Notebook:
   ```bash
      jupyter notebook Credit_Card_Fraud_Detection.ipynb

3. Run the cells step-by-step to train and test the model.

## Dataset
The dataset includes:

Time: Seconds elapsed between this transaction and the first transaction.
V1-V28: Anonymized features from PCA transformations.
Amount: The transaction amount.
Class: Target variable (1 for fraud, 0 for non-fraud).

## Results
The model's performance is evaluated to demonstrate its ability to correctly classify fraudulent transactions.

## Future Improvements
Experimenting with advanced models such as Random Forest or Neural Networks.
Implementing oversampling techniques like SMOTE for handling data imbalance.
Tuning hyperparameters for model optimization.

## Contributing
Contributions are welcome! Fork the repository, make your improvements, and submit a pull request.
