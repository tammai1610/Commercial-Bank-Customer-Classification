# Bank Customer Churn Prediction & Segmentation Project


**📈 Data Overview**
<br> This project focuses on preparing and analyzing bank customer data for developing machine learning models to predict customer churn and create meaningful customer segments. The dataset contains 10,000 customer records with 13 features including demographic information, financial behavior, and product usage patterns. This foundational analysis aims to establish a robust data pipeline for subsequent machine learning model development.

**🧐 Project Purpose**
<br> The primary objective is to prepare a comprehensive dataset and perform exploratory data analysis as groundwork for:

-  Developing predictive models to identify customers at risk of churning
-  Creating customer segmentation models to understand distinct customer groups
-   Building an automated system for early churn detection

**🔍 Key Metrics & Findings**
<br>_Churn Rate Overview_
- Overall churn rate: 20.37% (2,037 out of 10,000 customers)
- Highest churn observed in Germany (32.4%)
- Lower churn rates in France (16.2%) and Spain (16.7%)

_Demographics_
- Age group 46-60 shows highest churn rate (40.5%)
- Customers with multiple products have higher retention
- Credit score shows minimal correlation with churn

_Customer Behavior_
- Inactive customers more likely to churn
- Balance-to-salary ratio impacts churn decisions
- Product usage patterns differ among churned customers

**🛠️ Technical Implementation** [(Code Details)](https://github.com/tammai1610/Commercial-Bank-Customer-Classification/blob/main/BankCustomerPrep.ipynb)
- _Pandas_ for data manipulation
- _Matplotlib_ and _Seaborn_ for data visualization
- _Jupyter Notebook_ as the development environment


**🚀 Next Steps: Preparing for Machine Learning Model**

_1. Implement Predictive Modeling_
- Develop a churn prediction model using machine learning techniques like Logistic Regression or Random Forest predict which customers are at risk of churning.
- Train the model using key features such as age, geography, product usage, complaints, and satisfaction scores to improve predictive accuracy.

_2. Create Automated Monitoring System_
- Build a real-time churn monitoring system that continuously tracks customer activity and behavior. This system can trigger alerts when high-risk churn patterns are detected, enabling timely interventions.

**💡 Conclusion**
<br> This preparation phase establishes a robust foundation for developing sophisticated machine learning models for both churn prediction and customer segmentation. The cleaned and engineered dataset provides the necessary groundwork for building accurate and reliable predictive models.
