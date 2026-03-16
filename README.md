# Employee Turnover Analysis – Salifort Motors

## Project Overview
This project is part of the **Google Advanced Data Analytics Capstone**. The goal is to analyze employee turnover at Salifort Motors and predict which employees are likely to leave. Insights from this analysis help improve retention, reduce costs, and inform HR decisions.

---

## Dataset
- **Rows:** 14,999  
- **Columns:** 10 variables:  
  - `satisfaction_level` – Employee satisfaction score  
  - `last_evaluation` – Last performance evaluation score  
  - `number_of_projects` – Total projects assigned  
  - `average_monthly_hours` – Average monthly work hours  
  - `years_at_company` – Tenure in years  
  - `work_accident` – Work accident status  
  - `left` – Employee left (target)  
  - `promotion_last_5_years` – Promotion status  
  - `department` – Department  
  - `salary` – Salary level  

---

## Key Insights
- Higher workload and longer hours correlate with higher turnover.  
- Optimal workload appears to be **3–4 projects**, with low turnover.  
- Employees leaving either worked **very few** or **very many hours**.  
- Most employees work above standard monthly hours (~167 hours), indicating potential overwork.

---

## Modeling
- **Models Used:** Logistic Regression, Decision Tree, Random Forest, XGBoost  
- **Evaluation Metrics (Logistic Regression):**  
  - Accuracy: 83%  
  - Precision: 50%  
  - Recall: 17%  
  - F1-Score: 26%  
  - AUC: 0.83  
- **Key Features:** satisfaction level, promotion history, salary, workload, years at company  

---

## Recommendations
- Focus retention efforts on employees with **high workload or low satisfaction**.  
- Provide **career development opportunities** for at-risk employees.  
- Adjust workloads to reduce excessive monthly hours.  
- Build HR dashboards for early identification of high-risk employees.

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Data Visualization:** Boxplots, Histograms, AUC/ROC curves  
- **Machine Learning:** Logistic Regression, Decision Tree, Random Forest, XGBoost  

---

## Ethical Considerations
- All data is **anonymized** to maintain employee privacy.  
- Model outputs are intended for **supporting HR decisions**, not penalizing employees.  
- Ensure transparency to avoid bias in predictions.  

---
