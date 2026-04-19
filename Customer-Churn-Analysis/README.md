#  Customer Churn Analysis
### Telecom Customer Retention | Predictive Analytics

##  Business Problem
A telecom company losing 26.6% of customers monthly — 
representing $139K in lost monthly recurring revenue.
This analysis identifies who churns, why they churn, 
and what the business can do to stop it.

##  Project Structure
- `Customer_Churn_Analysis.ipynb` — Full analysis notebook
- `feature_importance.png` — Top churn drivers chart
- `dashboard/` — Power BI dashboard screenshots
  
##  Key Findings
1. 88% of churners were on month-to-month contracts
2. Fiber optic customers churn at highest rate despite paying most
3. First 12 months is the critical retention window
4. Electronic check users show lowest commitment

##  Model Results
| Model | Accuracy | Churn Recall |
|-------|----------|--------------|
| Logistic Regression | 79% | 52% |
| Random Forest | 78% | 46% |

**Best Model: Logistic Regression** — chosen for higher churn recall

##  Business Recommendations
- Offer discounts to upgrade month-to-month to annual contracts
- Launch onboarding program for customers in first 12 months
- Review fiber optic pricing — highest churn, highest cost
- Encourage auto-pay enrollment to reduce electronic check churn

##  Tools Used
Python · Pandas · Scikit-learn · Matplotlib · Power BI

## 📊 Dashboard Preview
![Dashboard](dashboard/dashboard_screenshot.png)
