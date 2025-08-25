## 💳 Fraud Detection Model

## 📌 Project Overview

This project aims to detect fraudulent financial transactions using Machine Learning. The dataset contains various transaction details, and the goal is to classify whether a transaction is fraudulent or legitimate.

-I built a machine learning pipeline that includes:

 - Data cleaning (handling missing values, outliers, and multicollinearity)

 - Feature engineering & selection

 - Model training & evaluation

 - Deployment using Streamlit for real-time predictions

---

## Dataset

download the dataset from kaggle 

[link](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download)

---

## ⚙️ Tech Stack

- Languages: Python

- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

- Deployment: Streamlit

- Model Storage: Pickle

---

## 🚀 How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/yourusername/Fraud-Detection.git
cd Fraud-Detection

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook "Fraud Detection model.ipynb"

4️⃣ Run the Streamlit App

cd streamlit_app
streamlit run app.py

---

## 📊 Model Training & Evaluation

- Trained multiple models (Logistic Regression, Random Forest, etc.)

- Selected the best-performing pipeline

- Evaluated with Accuracy, Precision, Recall, F1-score, ROC-AUC

---

## 🔑 Key Insights

- Features such as transaction amount, old balance, and new balance are strong predictors of fraud.

- Fraudulent transactions often show unusual balance changes.

---

## 🖥️ Streamlit Deployment

The app allows users to input transaction details and get a real-time fraud prediction.
Example:

- Input: amount=5000, oldbalanceOrg=10000, newbalanceOrig=2000, ...

- Output: ⚠️ Fraudulent Transaction

---
## 📸 Demo

https://github.com/user-attachments/assets/2e9971ff-c90b-4039-93bd-832b4f67de06

---

## 📌 Future Improvements

- Use deep learning models (e.g., LSTMs for sequential patterns)

- Implement SMOTE or advanced balancing for imbalanced data

- Deploy on cloud (AWS/GCP/Heroku) for production use

---
## 👩‍💻 Author

Helly Prajapati
📧 hellyprajapati@example.com

💼 LinkedIn
 | 🐙 GitHub
 
---
## Thank You for Visit! 
