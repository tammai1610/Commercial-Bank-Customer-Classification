# Bank Customer Churn Prediction & Segmentation Project


**📈 Data Overview**
<br> This project focuses on preparing and analyzing bank customer data for developing machine learning models to predict customer churn and create meaningful customer segments. The dataset contains 10,000 customer records with 13 features including demographic information, financial behavior, and product usage patterns. This foundational analysis aims to establish a robust data pipeline for subsequent machine learning model development.

**🧐 Project Summary**

- In my deep dive into bank customer churn, I discovered a fascinating pattern: German customers were leaving at alarming rates, while younger clients across all regions seemed equally eager to explore other options. Through careful analysis, I found that inactive customers were like silent alarm bells, signaling their eventual departure through quiet disengagement. My investigation revealed that clients with fewer financial products were more likely to leave, suggesting a clear link between product diversity and loyalty. Armed with these insights, I developed targeted solutions: personalized products for different age groups and smart engagement strategies to keep customers actively invested in their banking journey.

**🔍 Key Metrics & Findings**
* **Overall churn rate:** 20.37% (2,037 out of 10,000 customers).

* **Geographical Breakdown:**

    * **Germany:** Highest churn rate at 32.4%—possible dissatisfaction with product offerings or service.

    * **France:** Lower churn at 16.2%, indicating stronger retention strategies.

    * **Spain:** Churn rate at 16.7%, requiring moderate intervention.

* **Demographics:**

    * Customers aged 46-60 have the highest churn rate (40.5%), likely due to evolving financial needs.

    * Younger customers (18-30) churn at 25.6%, showing potential dissatisfaction with banking solutions.

    * Customers with multiple financial products retain better, highlighting the importance of product bundling.

* **Customer Behavior:**

    * Inactive customers are 3.2x more likely to churn compared to engaged users.

    * Balance-to-salary ratio above 3.0 is a strong churn predictor—higher wealth customers may seek better financial products elsewhere.

    * Customers using fewer than 2 financial services have a 45% higher churn rate.

**💡 Recommendations**

* **Targeted Retention Programs for High-Churn Segments:**

    * Develop personalized financial products for customers aged 46-60 to increase retention.

    * Enhance service offerings in Germany to improve customer satisfaction.

* **Improve Engagement Among Inactive Customers:**

    * Introduce automated alerts & personalized emails encouraging service utilization.

    * Offer exclusive incentives (discounted fees, better savings rates) for low-engagement customers.

* Optimize Product Offerings Based on Behavior Analytics:

    * Encourage cross-selling financial services to increase retention.

    * Balance-to-salary monitoring system: Identify customers at high churn risk and offer customized loyalty benefits.

**🛠️ Technical Implementation** [(Code Details)](https://github.com/tammai1610/Commercial-Bank-Customer-Classification/blob/main/BankCustomerPrep.ipynb)
- _Pandas_ for data manipulation
- _Matplotlib_ and _Seaborn_ for data visualization
- _Jupyter Notebook_ as the development environment


**💡 Conclusion**
- Through this comprehensive analysis of 10,000 bank customers, I uncovered critical patterns in customer churn that demand immediate attention. The stark contrast in churn rates—from Germany's concerning 32.4% to France's more stable 16.2%—highlights the need for region-specific interventions. The revelation that customers aged 46-60 have a 40.5% churn rate, combined with the finding that inactive customers are 3.2x more likely to leave, points to clear opportunities for targeted retention strategies. 
- By implementing the recommended personalized product offerings and engagement initiatives, particularly in high-risk segments, the bank can work toward reducing its overall 20.37% churn rate. The data pipeline and analysis framework established here provide a solid foundation for deploying machine learning models that can predict and prevent customer churn before it occurs.
