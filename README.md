##Financial Fraud Detection System 🚀
This repository contains a machine learning solution for detecting fraudulent financial transactions. The project includes a complete data analysis pipeline and a real-time web application for fraud prediction.

📊 Project Context
Financial fraud is a significant challenge for modern banking. This project uses a synthetic financial dataset containing over 6.3 million transactions to identify patterns of fraudulent activity. The analysis specifically focuses on high-risk transaction types such as TRANSFER and CASH_OUT.

Key Features Analyzed:
Transaction Type: Categorical data (PAYMENT, TRANSFER, CASH_OUT, DEBIT, CASH_IN).

Transaction Amount: The total value of the transaction.

Account Balances: Opening and closing balances for both the sender (Orig) and receiver (Dest).

Target Variable: isFraud (Binary classification).

🛠️ Technical Stack
Data Processing: Python, Pandas, NumPy.

Visualization: Matplotlib, Seaborn.

Machine Learning: Scikit-Learn (using a Pipeline with StandardScaler and OneHotEncoder).

Deployment: Streamlit (Web UI).

Model Storage: Joblib (for .pkl serialization).

📈 Model Performance
The machine learning pipeline was trained and tested on millions of records, achieving a high accuracy score:

Testing Accuracy: 94.68%.

Evaluation: The project utilizes a confusion matrix to validate the balance between precision and recall.

📂 File Structure
analysis_model.ipynb: The main notebook containing data cleaning, Exploratory Data Analysis (EDA), and model training.

app.py: The script for the interactive Streamlit web application.

fraud_detection_model.pkl: The saved machine learning pipeline ready for production use.

fraud analysis.ipynb: Preliminary data exploration and visualization.

🚀 How to Run
Install dependencies:

Bash

pip install streamlit pandas joblib scikit-learn
Launch the Web App:

Bash

streamlit run app.py
Use the interface: Enter transaction details into the sidebar and click Predict to see if a transaction is flagged as potential fraud.
