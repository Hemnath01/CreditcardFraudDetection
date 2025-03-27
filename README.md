# CreditcardFraudDetection

This project aims to build a Machine Learning model to detect fraudulent credit card transactions. The model is trained to distinguish between legitimate and fraudulent transactions, minimizing false positives while maximizing fraud detection accuracy.

**Dataset**
The dataset contains transaction details, including:

trans_date_trans_time - Timestamp of transaction

cc_num - Credit card number

merchant - Merchant name

category - Purchase category

amt - Transaction amount

city, state, lat, long - Location details

is_fraud - Target variable (1 = Fraud, 0 = Legitimate)

**Objectives**


Preprocess Data - Handle missing values, encode categorical features, and normalize numerical data.

Train Machine Learning Models - Implement Random Forest Classifier.

Optimize Performance - Tune hyperparameters for improved fraud detection.

Evaluate the Model - Use Accuracy, Precision, Recall, F1-score, and ROC-AUC.


 **Steps to Run the Project**


1️⃣ Clone the Repository

2️⃣ Load the Dataset
Ensure the dataset file (fraudTest.csv) is inside the project folder.

3️⃣ Run the Jupyter Notebook (Google Colab)
Open CreditCardFraudDetection.ipynb

Run all cells to execute data preprocessing, model training, and evaluation

