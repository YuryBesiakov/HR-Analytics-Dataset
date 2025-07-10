# 📊 Employee Attrition Prediction — ML Project

![Infographic](images/infog.png) 

---

## 📌 Project Overview

This project analyzes employee attrition patterns using the [HR Analytics Dashboard - Employee Attrition Dataset](https://www.kaggle.com/datasets/anubhav761/hr-analytics-dashboard-employee-attrition) from Kaggle. The goal is to predict whether an employee is likely to leave the company using machine learning techniques and also to model and predict monthly income based on various individual and job-related features.

---

## 🎯 Objectives

- Perform **Exploratory Data Analysis (EDA)** to understand key drivers of attrition.
- Build and evaluate classification models (e.g., Logistic Regression, Random Forest, XGBoost).
- Communicate insights that HR teams can use to reduce attrition risk.

---

## 🛠️ Tools & Libraries Used

- **Python**: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, XGBoost
- **Jupyter Notebook**
- **Git & GitHub**
- *(Optional)* Streamlit for future deployment

---

## 📁 Project Structure

```
employee-attrition-ml/
│
├── module/                    # Your Python module or notebook(s)
├── images/
│   └── infog.png              # Infographic
├── README.md                  # Project overview
└── requirements.txt           # (Optional) dependencies
```

---

## 📈 About the Dataset

- **Source:** [Kaggle HR Analytics Dashboard - Employee Attrition](https://www.kaggle.com/datasets/anubhav761/hr-analytics-dashboard-employee-attrition)  
- **Records:** 1,470 employees  
- **Features:** Demographics, job satisfaction, compensation, career progression, and more.
- **Target:** `Attrition` — whether the employee has left the company (Yes/No). `MonthlyIncome` - Monthly income of the employee.

<details>
<summary>📄 Click for column descriptions</summary>

1. **Age** — Employee age  
2. **Attrition** — Target: Has the employee left? (Yes/No)  
3. **Business Travel** — Travel frequency (Rarely, Frequently, Non-Travel)  
4. **Daily Rate**, **Hourly Rate**, **Monthly Income**, etc. — Compensation details  
5. **Department**, **Job Role**, **Job Level** — Position details  
6. **Job Satisfaction**, **Environment Satisfaction**, **Relationship Satisfaction** — Surveys  
7. **Over Time**, **Distance From Home**, **Years At Company**, **Years Since Last Promotion**, and more.

</details>

---

## 🧪 Main Steps

1. **EDA:** Explore distributions, missing values, and correlations.
2. **Data Preprocessing:** Handle missing data, encode categorical variables, scale features.
3. **Modeling:** Train baseline & advanced classifiers.
4. **Evaluation:** Confusion matrix, ROC-AUC, precision, recall, feature importance.
5. **Insights & Next Steps:** Suggest HR actions, limitations, and possible improvements.

---

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.84     | 0.73      | 0.62   | 0.67     | 0.85    |
| Random Forest       | 0.86     | 0.76      | 0.65   | 0.70     | 0.87    |
| XGBoost             | 0.87     | 0.78      | 0.68   | 0.72     | 0.89    |

---

## ⚙️ How to Run

- Clone the repo
- Install dependencies (if you have a `requirements.txt`)
- Run the notebook(s) in the `module/` folder step-by-step

```bash
git clone https://github.com/YuryBesiakov/HR-Analytics-Dataset
```

---

## ✅ Key Results

Example: *Random Forest achieved ~85% accuracy and identified overtime and job satisfaction as top attrition drivers.*

---

## 🔄 Reflection & Future Improvements

- **Limitations:** The dataset is relatively small and specific to one company context. Results may not generalize.
- **Learnings:** This project strengthened my experience with end-to-end data pipelines, model selection, and translating findings into actionable recommendations.

---

## 🚀 Next Steps

- Add more advanced explainability (e.g., SHAP or LIME)
- Test additional models
- Deploy a simple demo app (Streamlit or Gradio)

---
