# 📊 Customer Churn Prediction & Retention Strategy

A machine learning solution that predicts customer churn in the telecommunications industry and identifies actionable retention strategies. This project combines predictive modeling with business analysis to reduce churn rates and improve customer lifetime value.

---

## 📊 Business Problem

Customer churn costs telecom companies an estimated 15–25% of annual revenue. Acquiring new customers costs 5–7 times more than retaining existing ones, making churn prevention a critical business priority.

This project addresses three key challenges:

1. **Early identification** – Which customers are at highest risk of churning?
2. **Root cause analysis** – What factors drive customers to leave?
3. **Targeted intervention** – What retention strategies will be most effective?

The predictive model enables proactive outreach to at-risk customers, allowing the business to reduce churn through targeted offers, service improvements, and personalized engagement.

---

## 📁 Dataset Overview

The dataset contains **7,000+ customer records** from a telecommunications provider, including:

- Customer demographics (age, gender, dependents)
- Service subscriptions (phone, internet, streaming, security)
- Account details (contract type, payment method, tenure)
- Billing information (monthly charges, total charges)
- Churn status (whether the customer canceled service)

**Key attributes**: `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`, `tenure`, `PhoneService`, `InternetService`, `Contract`, `MonthlyCharges`, `TotalCharges`, `Churn`

---

## 🛠️ Tools Used

- **Python** – Data processing and machine learning
- **Pandas & NumPy** – Data manipulation and analysis
- **Scikit-learn** – Model development and evaluation
- **XGBoost** – Gradient boosting for classification
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis and documentation

---

## 🔍 Key Insights

1. **Month-to-month contracts have a 42% churn rate**, compared to just 3% for two-year contracts. Contract length is the strongest predictor of customer retention.

2. **Customers without tech support are 2.5 times more likely to churn**, indicating that service quality and customer assistance are critical retention factors.

3. **The first 12 months are the highest-risk period**, with 50% of churn occurring among customers with less than one year of tenure. Early engagement programs are essential.

4. **Fiber optic internet customers churn at 41%, versus 19% for DSL**, suggesting pricing or service quality issues specific to this segment.

5. **Electronic check users have a 45% churn rate**, compared to 16% for automatic payment users. Payment friction contributes to attrition.

6. **Senior citizens churn at 42%, significantly higher than the 23% average**, pointing to a need for tailored support and simplified service options for this demographic.

---

## 💡 Business Recommendations

**Incentivize long-term contracts**  
Offer discounts or perks (e.g., free premium channels) for customers who switch from month-to-month to annual or two-year contracts. Target this campaign at customers with 6–12 months of tenure.

**Bundle value-added services**  
Include tech support and online security in mid-tier and premium plans by default. For existing customers without these services, offer a 3-month trial to demonstrate value.

**Launch an early engagement program**  
Implement proactive outreach at 30, 60, and 90 days for new customers. Focus on onboarding support, satisfaction checks, and early problem resolution.

**Address fiber optic service issues**  
Conduct a service quality audit for fiber optic customers. Consider pricing adjustments or performance improvements to reduce churn in this high-value segment.

**Reduce payment friction**  
Encourage automatic payment enrollment through incentives (e.g., $5/month discount). Simplify the payment process and offer multiple payment options.

**Create a senior customer support program**  
Develop simplified billing, dedicated support lines, and in-home setup assistance for senior customers. Proactively reach out to this segment with retention offers.

---

## 🧠 Machine Learning Analysis

The project developed a classification model to predict customer churn with the following approach:

- **Data preprocessing** – Handled missing values, encoded categorical variables, and scaled numerical features
- **Feature engineering** – Created derived features such as tenure categories, service usage patterns, and payment behavior indicators
- **Model selection** – Evaluated multiple algorithms (Logistic Regression, Random Forest, XGBoost) and selected XGBoost for its superior performance
- **Class imbalance handling** – Applied SMOTE (Synthetic Minority Over-sampling Technique) to address the 73/27 split between retained and churned customers
- **Hyperparameter tuning** – Optimized model parameters using cross-validation to maximize F1 score and recall

**Model performance:**
- **Accuracy**: 82%
- **Precision**: 70%
- **Recall**: 58%
- **F1 Score**: 64%
- **ROC-AUC**: 0.86

The model prioritizes recall to minimize false negatives—ensuring that at-risk customers are not missed by the retention program. Feature importance analysis identified contract type, tenure, and service subscriptions as the top predictors.

---

## 📌 Conclusion

This project demonstrates how predictive analytics can transform customer retention from a reactive process to a proactive strategy. By identifying at-risk customers early and understanding the drivers of churn, the business can implement targeted interventions that reduce attrition and improve profitability.

The analysis yielded actionable recommendations with measurable impact potential. If applied to the current customer base, these strategies could reduce churn by an estimated 20%, saving the business approximately $680,000 annually.

This project highlights expertise in machine learning, statistical analysis, data-driven decision-making, and translating technical insights into business value.

---

## 📂 Repository Contents

- `customer churn prediction.ipynb` – Machine learning model development
- `TCA.ipynb` – Exploratory data analysis and visualizations
- `Customer Churn.csv` – Source data
- `Teco Customer Churn Analysis.pdf` – Detailed analysis report
- `README.md` – Project documentation

---

## 👤 Author

**Vinay Sai**  
Data Scientist | Machine Learning | Predictive Analytics

- [GitHub](https://github.com/vinaysai7)
- [LinkedIn](https://www.linkedin.com/in/bandela-vinay-babu)

---

**Tags**: Machine Learning, Customer Churn, Predictive Analytics, Python, XGBoost, Classification
