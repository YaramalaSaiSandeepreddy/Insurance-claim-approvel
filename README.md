# Insurance-claim-approvel
# 🛡️ Insurance Claim Approval Prediction — Random Forest Project

## 📌 Project Overview

This project builds a Machine Learning model to predict whether an insurance claim will be approved or rejected based on customer, policy, and claim details. The model uses a Random Forest Classifier and includes feature engineering to improve prediction performance.

The goal is to help insurance companies automate claim decision processes and detect risky claims efficiently.

---

## 🎯 Objectives

* Analyze insurance claim dataset
* Perform feature engineering
* Train a Random Forest model
* Evaluate model performance using multiple metrics
* Visualize results

---

## 📂 Dataset

The dataset contains information such as:

* Customer demographics (Age, Gender, Employment Status)
* Financial details (Annual Income, Premium Amount)
* Policy information (Policy Type, Duration, Coverage Amount)
* Claim details (Claim Amount, Past Claims, Fraud Risk)
* Target variable: Claim Approval (0 = Rejected, 1 = Approved)

File used:

```
insurance_claim_approval.csv
```

---

## 🧪 Feature Engineering

New features created:

* Claim_Income_Ratio → Claim amount relative to income
* Risk_Score → Based on past claims
* Long_Policy → Policy duration indicator
* High_Claim → High claim flag
* Reliable_Payer → Payment reliability flag

Categorical variables encoded using one-hot encoding.

---

## 🤖 Model Used

Random Forest Classifier with:

* 200 trees
* Fixed random state for reproducibility

---

## 📊 Evaluation Metrics

Model performance evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC AUC
* Confusion Matrix
* Classification Report

---

## 📈 Results

The model achieved very high performance:

* Accuracy ≈ 99%
* Precision ≈ 0.99
* Recall ≈ 1.00
* F1 Score ≈ 0.99
* ROC AUC ≈ 0.999

Visualization included a bar chart comparing metrics.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab / Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

```
pip install pandas numpy scikit-learn matplotlib
```

3. Place dataset file in project folder
4. Run the notebook or script

---

## 📁 Project Structure

```
├── insurance_claim_approval.csv
├── insurance_claim_model.ipynb
├── README.md
```

---

## 💡 Future Improvements

* Hyperparameter tuning
* Handle class imbalance
* Deploy as web app (Flask / Streamlit)
* A
