# Loan Approval Prediction 🎯

This project is a machine learning-based web application that predicts whether a loan application will be approved or not. It uses various applicant details such as income, credit history, employment status, and more to make predictions using a trained ML model.

## 📌 Project Description

This project is built using Python and Jupyter Notebook for model training and Streamlit for creating the web interface. The model is trained on historical loan application data to learn patterns and predict future approvals. It helps banks or financial institutions speed up the initial assessment of loan applications.

## 📁 Features

- Model training using classification algorithms
- Accuracy evaluation
- Web-based user interface using Streamlit
- Input form for real-time prediction

## 🛠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
- Streamlit
- Git & GitHub

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/tanuja42/Loan_Approval_prediction.git
cd Loan_Approval_prediction

### Step 2:Install dependencies
It's recommended to create a virtual environment first.
pip install -r requirements.txt
Or manually install:
pip install pandas numpy scikit-learn streamlit


### Step 3: Run the app
streamlit run app.py

📊 Dataset
The dataset used in this project contains features like:
-Education
-Applicant Income
-Loan Amount
-Credit History
-Property Area
This dataset was taken from Kaggle's Loan Prediction Problem.

📈 Model Performance
The model is evaluated using accuracy score, confusion matrix, and cross-validation techniques. Logistic Regression gave the best result with an accuracy of ~X% (update with actual).

💡 Future Improvements
Add more ML models like Random Forest or XGBoost
Improve the Streamlit UI design
Add model explainability (e.g., SHAP values)
Deploy on cloud (Heroku, Streamlit Cloud, etc.)

👩‍💻 Author
Tanuja Mahendrakar
GitHub: @tanuja42

