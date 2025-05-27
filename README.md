# 📊 Customer Churn Analysis

## 📝 Project Overview

Customer Churn Prediction(CCP) is a process of analyzing and predicting the behavior of new and existing customers or software users. This mechanism is important in various industries including telecommunications, Petroleum, Business, and information technology. The ability to predict customer churn is defined as the probability of customers discontinuing a service which can transform risk into opportunities. These include revenue growth, increased customer interaction, build a positive business reputation. This analysis can be done using several machine learning models. In this paper, the models used are Logistic Regression, KNN, XGBOOST, and SVM.

It also highlights the comparative analysis of these models and concludes which model is suitable for achieving optimal results and which model is not suitable. These results or insights can be used by businesses to mitigate customer churn, which will ultimately accelerate revenue growth.

---

## 🧰 Technologies Used

* Python (Jupyter Notebook / Google Colab)
* Pandas, NumPy
* Matplotlib, Seaborn (for visualization)
* Scikit-learn (for machine learning models)
* Logistic Regression, Decision Tree, Random Forest, KNN, and more
* Classification metrics (Accuracy, Precision, Recall, F1 Score, AUC-ROC, AUC-PR, LogLoss)

---

## 📁 Project Structure

```
CUSTOMER-CHURN-ANALYSIS/
├── CUSTOMER CHURN ANALYSIS.ipynb   # Main Jupyter Notebook
├── customer_data.csv               # Dataset used (if applicable)
└── README.md                       # Project documentation
```

---

## 📊 Features and Workflow

1. **Data Loading**
   Load and inspect the dataset for missing values and anomalies.

2. **Exploratory Data Analysis (EDA)**

   * Understand data distribution.
   * Identify trends and patterns affecting churn.

3. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical features
   * Feature scaling

4. **Model Building**

   * Train multiple classifiers
   * Evaluate using cross-validation

5. **Model Evaluation**

   * Confusion Matrix
   * ROC-AUC Curve
   * Precision, Recall, F1 Score

6. **Conclusion**
   Summarize model performance and recommend actions based on results.

---

## ✅ Results

* Best model achieved is SVM with **52% accuracy**.
* Top influencing features: *Tenure, Monthly Charges, Contract Type*, etc.
* Insights provided on customer segments more likely to churn.

![image](https://github.com/user-attachments/assets/35c9a8fb-f83a-48b3-961a-24ba452ff825)


---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   ```

2. Open `CUSTOMER CHURN ANALYSIS.ipynb` using Jupyter Notebook or Google Colab.

3. Install required dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Run all cells to execute the workflow.

---
