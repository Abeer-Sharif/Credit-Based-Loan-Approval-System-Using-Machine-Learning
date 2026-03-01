# 🚀 Credit-Based Loan Approval System (ML)
A machine learning-powered system that predicts whether a loan should be approved based on applicant data. Built with Python, Pandas, Scikit-learn, and real-world loan application records.
---

## 🧠 What This Project Does

This repo contains a model that:
✔ Ingests loan application records  
✔ Cleans and preprocesses the data  
✔ Encodes categorical features  
✔ Trains ML models (trees, ensembles)  
✔ Selects the best model through validation  
✔ Predicts loan approval (Yes/No)

This is perfect for understanding real-life model building, evaluation, and deployment readiness.

---

## 🧩 Dataset Snapshot

Features include:

| Feature | Meaning |
|---------|---------|
| `ApplicantIncome` | Main applicant salary |
| `CoapplicantIncome` | Co-applicant salary |
| `LoanAmount` | Loan amount requested |
| `Credit_History` | Good / Bad credit history |
| `Gender`, `Marital_Status`, `Property_Area`, etc. | Categorical info |

Target:
- `Loan_Status`: Approved (`Y`) or Rejected (`N`)

Data source: `loan_approval_data.csv`

---

## 🛠 Tech Stack

| Layer | Tools |
|-------|-------|
| Language | Python |
| Data | Pandas, NumPy |
| ML | Scikit-learn |
| Visualization | Seaborn, Matplotlib |
| Notebook | Jupyter |

---

## 🔁 Pipeline Overview

1. **Load & Explore Data**  
   Missing values, distributions, imbalance checks

2. **Preprocess**
   - Encode categorical columns (One-Hot)
   - Scale numeric features (optional)
   - Train/validation/test splits

3. **Model Training**
   - Baseline: Logistic Regression
   - Tree-based: Decision Tree, Random Forest
   - Pruning & hyperparameter tuning

4. **Model Selection**
   - Validation set for tuning
   - Test set for final evaluation

5. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

---

## 📊 Quick Results

This project evaluates multiple models and selects the best one **without leaking test data** during tuning.

---

## 🚧 Usage

1. Clone the repo

```sh
git clone https://github.com/Abeer-Sharif/Credit-Based-Loan-Approval-System-Using-Machine-Learning.git

##Install requirements
pip install pandas numpy scikit-learn seaborn matplotlib
