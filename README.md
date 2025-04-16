##  Invoice Payment Delay Prediction System  
**Predict Delay | Classify Risk | Explain Models | Drive Business Insights**

A complete ML system to analyze and predict invoice payment delays using real-world MySQL data. Built with XGBoost, SHAP, and Seaborn — this project goes beyond predictions to offer clear dates, risk buckets, business dashboards, and model transparency.



##  Problem Statement

>  Companies often struggle with delayed payments, affecting cash flow and risk assessment.  
>  This project solves it by predicting:
> - When an invoice will actually get paid (`predicted_clear_date`)
> - How many days it will be delayed (`delay_days`)
> - Whether it's likely to be late (`is_delayed`)
> - What risk bucket it belongs to (`aging_bucket`)

---

##  Features Overview

| Module                     | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
|  **Delay Prediction**    | Predict number of delay days (regression) with XGBoost, RF, Linear models   |
|  **Risk Classification** | Predict if an invoice is delayed or not (classification)                    |
|  **Delay Bucketing**     | Classify invoices into buckets: `0-15`, `16-30`, `31-45`, `46-60`, `60+`     |
|  **Clear Date Estimator**| Add delay to due date to generate `predicted_clear_date`                   |
|  **Business Dashboards** | Visualize trends by region, customer, credit score, invoice amount          |
|  **SHAP Explainability** | Understand how features impact predictions (both local + global)            |

---

##  Tech Stack

- **Languages:** Python, SQL  
- **Database:** MySQL (via SQLAlchemy)  
- **ML Models:** XGBoost, Random Forest, Linear & Logistic Regression  
- **Visualization:** Seaborn, Matplotlib, SHAP  
- **EDA Tool:** Sweetviz  
- **Libraries:** Pandas, Faker, Joblib, Scikit-learn  
- **Tools:** Jupyter Notebook, MySQL Workbench, GitHub

---


