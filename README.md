# 🏦 Loan Eligibility Prediction

A Machine Learning-powered web application that predicts whether a user is eligible for a loan based on key financial and personal details. This project includes a trained model, preprocessing pipeline, and a user-friendly web interface.

---

## 📌 Overview

Financial institutions often need quick, data-driven tools to assess an applicant's loan eligibility. This project automates that assessment using a classification model trained on historical loan data.

The system consists of:
- A data science workflow (via Jupyter Notebook)
- A trained Logistic Regression model
- Feature scaler
- A web app (Flask or Streamlit) for interactive user input and predictions

---

## 💡 Features

- Predicts loan eligibility in real-time
- Clean and responsive UI
- Preprocessing and trained model included
- Extensible codebase for retraining or updating the model

---

## 📁 Project Structure

```
loan-eligibility-prediction/
├── Loan Eligibility (Final Project).ipynb  # Notebook for training and analysis
├── model.pkl                               # Trained ML model
├── scaler.pkl                              # Scaler used in preprocessing
├── web app.py                              # Web application script
└── README.md                               # Project documentation
```

---

## ⚙️ How to Run

### 1. Clone this Repository

```bash
git clone https://github.com/your-username/loan-eligibility-prediction.git
cd loan-eligibility-prediction
```

### 2. Install Dependencies

You can use a virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

Install necessary packages:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install pandas numpy scikit-learn flask streamlit joblib
```

### 3. Run the Web App

#### If you're using **Flask**:
```bash
python "web app.py"
```

Visit:
```
http://localhost:5000/
```

#### If you're using **Streamlit**:
```bash
streamlit run "web app.py"
```

Visit:
```
http://localhost:8501/
```

---

## 🧠 Model Overview

- **Algorithm:** Logistic Regression
- **Libraries:** scikit-learn, pandas, numpy
- **Training & Evaluation:** Handled in the Jupyter Notebook
- **Input Features:**
  - Gender, Married, Dependents, Education, Self_Employed
  - ApplicantIncome, CoapplicantIncome
  - LoanAmount, Loan_Amount_Term
  - Credit_History, Property_Area

---

## 📊 Example Inputs

| Feature              | Example Value     |
|----------------------|------------------|
| ApplicantIncome      | 5000             |
| LoanAmount           | 150              |
| Credit_History       | 1 (good history) |
| Property_Area        | Urban            |

---



## 🚀 Future Improvements

- Add user authentication
- Deploy to Heroku or Render
- Include model performance metrics
- Allow real-time retraining with uploaded datasets
- Create REST API version

---


## 🙌 Acknowledgements

- Kaggle Loan Prediction Dataset
- scikit-learn for ML pipeline
- Streamlit/Flask for UI
- Python open-source community

---

## 📬 Contact

Created by **[Your Name]**  
📧 Email: monisharajarathinam18@gmail.com 
🔗 GitHub: https://github.com/monisha-mba
