## Froud_detection
# 💳 AI-Powered Financial Fraud Detection System

An AI-powered Financial Fraud Detection System developed using **Machine Learning** to identify fraudulent financial transactions. The project uses the **Random Forest Classifier** to analyze transaction patterns and classify transactions as **Legitimate** or **Fraudulent**.

---

## 📌 Project Overview

Financial fraud has become one of the biggest challenges in digital payment systems. This project applies supervised machine learning techniques to detect fraudulent transactions based on historical transaction data.

The system preprocesses transaction data, trains a machine learning model, evaluates its performance, and predicts whether a new transaction is fraudulent.

---

## 🎯 Objectives

- Detect fraudulent financial transactions.
- Reduce financial losses caused by fraud.
- Improve transaction security.
- Build a machine learning model with high prediction accuracy.
- Allow users to predict fraud by entering transaction details.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Libraries Used

| Library | Purpose |
|----------|---------|
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning algorithms and preprocessing |

---

## 🤖 Machine Learning Algorithm

- Random Forest Classifier

---

## 📂 Dataset Information

The dataset contains financial transaction records with the following features:

| Feature | Description |
|----------|-------------|
| step | Time step of the transaction |
| type | Transaction type |
| amount | Transaction amount |
| nameOrig | Sender account ID |
| oldbalanceOrg | Sender balance before transaction |
| newbalanceOrig | Sender balance after transaction |
| nameDest | Receiver account ID |
| oldbalanceDest | Receiver balance before transaction |
| newbalanceDest | Receiver balance after transaction |
| isFraud | Fraud label (Target Variable) |
| isFlaggedFraud | Flagged suspicious transaction |

---

## 🔄 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Label Encoding
6. Correlation Analysis
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Fraud Prediction

---

## ⚙️ Data Preprocessing

- Checked missing values
- Removed duplicate records
- Label Encoding for categorical columns
- Correlation Matrix
- Feature Selection
- Train-Test Split

---

## 📊 Model Performance

Algorithm Used:

- Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 💻 Sample Prediction

### : Legitimate Transaction

**Input**

```text
Enter Step: 1
Enter Transaction Type: PAYMENT
Enter Amount: 9839.64
Enter Old Balance Origin: 170136.00
Enter New Balance Origin: 160296.36
Enter Old Balance Destination: 0.00
Enter New Balance Destination: 0.00
Enter isFlaggedFraud (0 or 1): 0
```

**Output**

```text
✅ Legitimate Transaction
```

---

### : Fraudulent Transaction

**Input**

```text
Enter Step: 1
Enter Transaction Type: TRANSFER
Enter Amount: 181.00
Enter Old Balance Origin: 181.00
Enter New Balance Origin: 0.00
Enter Old Balance Destination: 0.00
Enter New Balance Destination: 0.00
Enter isFlaggedFraud (0 or 1): 0
```

**Output**

```text
🚨 Fraudulent Transaction
```

---

## 📈 Prediction Labels

| Value | Meaning |
|-------|---------|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

---

## 📁 Project Structure

```
AI-Powered-Financial-Fraud-Detection/
│
├── Financial_Fraud_Detection.ipynb
├── fraud_detection_model.pkl
├── label_encoder.pkl
├── requirements.txt
├── README.md
├── dataset.csv
│
└── images/
    ├── correlation_matrix.png
    ├── confusion_matrix.png
    ├── fraud_distribution.png
    └── prediction_output.png
```

---

## ▶️ Installation

Clone the repository

```bash
https://github.com/Princeyadav8881/Froud_detection.git
```

Move into the project directory

```bash
cd Fraud_Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

---

## 📷 Output Screenshots

Add screenshots of:

- Dataset Preview
- Correlation Matrix
- Fraud Distribution
- Confusion Matrix
- Model Accuracy
- User Prediction Output
- **Prince Yadav<img width="816" height="537" alt="Screenshot_16-7-2026_121240_localhost" src="https://github.com/user-attachments/assets/afc861f8-4d73-49c4-835e-05f1906049da" />
<img width="969" height="668" alt="Screenshot_16-7-2026_12130_localhost" src="https://github.com/user-attachments/assets/cd0c757a-e1a3-4d46-8cef-c84aec632dee" />
<img width="1051" height="709" alt="Screenshot_16-7-2026_12121_localhost" src="https://github.com/user-attachments/assets/6404c1c5-85f3-40d7-9094-59fa48499d29" />
**

---

## 🚀 Future Improvements

- Deploy using Flask or Streamlit
- Real-time fraud detection
- Deep Learning models
- Explainable AI (SHAP/LIME)
- Interactive Dashboard
- API integration

---

 👨‍💻 Author

Prince Yadav

(B.Tech Computer Science & Engineering)


---

