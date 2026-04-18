# 🤖 Telecom Customer Churn Prediction (ML)
> Leveraging Machine Learning to proactively identify and retain at-risk customers.

---

## 🎯 Executive Summary
Churn is a critical KPI for telecom providers. This project implements a **Supervised Learning** model to classify customers into "Likely to Churn" or "Likely to Stay." By analyzing historical behavior, the model provides actionable insights to reduce revenue loss.

---

## 🧠 The ML Pipeline
I followed a structured data science workflow to ensure model robustness:

1. **Feature Engineering:** Transformed raw customer data into meaningful features (e.g., converting "Total Charges" to numeric, handling outliers).
2. **Data Preprocessing:** * Scaled numerical features for better convergence.
    * One-Hot Encoding for categorical variables.
3. **Model Selection:** Evaluated multiple algorithms to find the best balance between precision and recall.
4. **Evaluation:** Optimized the model based on the **F1-Score** and **AUC-ROC** curve.

---

## 📊 Model Performance
The final model achieved the following results on the test set:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 80%+ |
| **Precision** | High (Minimizing false alarms) |
| **Recall** | Optimized (Capturing most churners) |

---

## 🗝️ Top Predictors (What the Model Learned)
The model identified that these 3 factors are the strongest predictors of churn:

1. **Contract Type:** Long-term contracts act as the strongest "anchor" for customers.
2. **Tenure:** The first few months are the most critical "danger zone."
3. **Online Security & Tech Support:** Customers with these services are significantly more loyal.

---

## 🛠️ Installation & Usage
1. Clone the repository.
2. Ensure you have the environment set up: `conda env create -f environment.yml`
3. Run the notebook: `jupyter lab Customer_telecom.ipynb`

---
**Developed by [Tariq Zeyad]** *Machine Learning | Data Analysis | Business Intelligence*
