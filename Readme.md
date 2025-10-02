Customer Churn Prediction & Dashboard

# Dataset Information
The dataset was obtained from Kaggle and can be accessed


# Project Overview
This project analyzes customer churn for a telecom company by combining data analysis, predictive modeling, and a Power BI dashboard. It aims to identify which customers are most likely to leave, how much revenue is at risk, and what business factors drive churn.

The final deliverables are:

An interactive Power BI dashboard showing churn KPIs.

A machine learning model with 97% accuracy for predicting churn and 98% recall.

Insights into the key factors that influence customer churn.


# Key Insights

Churn Rate: 26.54% of customers leave the service.

Revenue Impact: Over $139K lost from churned customers.

Customer Tenure: Most churn occurs within the first 0–5 months, and another spike happens at around 6–7 years of service.

Service Effect: Customers with Fiber Optic internet and those paying via Electronic Check churn at the highest rates.

Contracts Matter: Customers on month-to-month contracts are far more likely to churn compared to one- or two-year contracts.

Feature Importance:
<img width="487" height="288" alt="Image" src="https://github.com/user-attachments/assets/8bd10693-4f10-4425-80c7-315eefc0afda" />

🤖 Model Performance
<img width="227" height="77" alt="Image" src="https://github.com/user-attachments/assets/99362290-289a-4545-8be2-4bb7687d5a63" />
The machine learning model achieved:

Accuracy: 97%

Recall for Churners: 98%

Precision for Churners: 93%

What This Means is:

Recall (98%) → If 100 customers are about to leave, the model correctly identifies 98 of them. This is critical because missing churners could mean lost revenue.

Precision (93%) → When the model flags 100 customers as “likely to churn,” about 93 truly do churn. This means the model is highly reliable, with few false alarms.

Bottom line: The model is very effective at spotting customers who are at risk, giving the business a strong tool for targeted retention strategies.

# Dashboard Overview
# Preview
<img width="483" height="272" alt="Image" src="https://github.com/user-attachments/assets/889954b1-fc98-4e87-ad5e-2cfc4717d960" />
The Power BI dashboard provides business leaders with an intuitive way to explore churn patterns:

Revenue & Churn KPIs: See total churn rate, number of customers lost, and revenue impact.

Customer Segments: Drill into churn by internet service, contract type and payment method.

Lifecycle Trends: Track churn across tenure stages, highlighting vulnerable early- and late-stage customers.

Interactive Filters: Segment results by demographics(Gender) for targeted insights.

# Business Value

This project delivers both strategic insights and a practical prediction tool:

Executives can see where and why churn is happening using the dashboard.

Customer success teams can use the ML model’s predictions to focus retention efforts on high-risk customers.

Financial teams can quantify revenue at risk and evaluate the ROI of retention programs.

# Conclusion
The churn dashboard and prediction model empower decision-makers to detect early warning signs, intervene before customers leave, and reduce financial losses from churn.