🛡️ Financial Fraud Detection System

This project is a comprehensive Machine Learning solution designed to detect fraudulent financial transactions. It includes data analysis, model training, and a real-time prediction interface built with Streamlit.

## 📌 Project Overview
Financial fraud costs the global economy billions annually. This project leverages historical transaction data to build a predictive model that identifies suspicious activities based on transaction types, amounts, and account balance changes.

### Key Features:
* **Data Exploration:** Detailed analysis of transaction patterns.
* **Machine Learning:** A robust classification pipeline (StandardScaler + OneHotEncoder + Classifier).
* **Web Interface:** An interactive dashboard for real-time fraud checking.
* **Scalability:** The model is trained on a dataset of over 6.3 million records.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Deployment:** Streamlit
* **Model Format:** Joblib (Pickle)

## 📂 Project Structure
| File | Description |
| :--- | :--- |
| `analysis_model.ipynb` | The core notebook containing EDA, Feature Engineering, and Model Training. |
| `app.py` | The Streamlit web application for end-users. |
| `fraud_detection_model.pkl` | The pre-trained machine learning pipeline. |
| `fraud analysis.ipynb` | Additional analysis and visualization of the dataset. |

## 📊 Model Performance
The model was evaluated using a testing dataset and achieved high reliability:
- **Testing Accuracy:** ~94.68%
- **Evaluation Metric:** Confusion Matrix (used to minimize false negatives).

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/fraud-analysis-project.git](https://github.com/your-username/fraud-analysis-project.git)
cd fraud-analysis-project
2. Install dependencies
Bash

pip install streamlit pandas joblib scikit-learn
3. Run the Application
Bash

streamlit run app.py
🖥️ How it Works
Input: Enter transaction details such as Type (e.g., Transfer, Cash Out), Amount, and Balances.

Process: The app.py loads the fraud_detection_model.pkl.

Output: The system instantly predicts whether the transaction is Fraudulent or Legitimate.

📝 License
This project is licensed under the MIT License.


---

### Tips for your GitHub:
1.  **Screenshots:** If you have run the `app.py`, take a screenshot of the Streamlit interface and add it to a folder named `img` in your repo, then link it in the README using `![App Screenshot](img/screenshot.png)`.
2.  **Dataset Link:** Since the dataset file (`AIML Dataset.csv`) is usually too
