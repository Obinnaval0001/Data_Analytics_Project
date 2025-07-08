# Bank-Churn-Prediction-and-Segmentation
## Project Description: 
The banking sector faces a significant challenge with customer churn, where customers discontinue their relationship with a financial institution. This project aims to analyze customer data to identify factors influencing churn and segment the bank’s customer base for targeted interventions. Using a dataset of 10,000 customers, the project explores customer demographics, account behaviors, and churn predictors to mitigate churn effectively.

## Key Questions
* What attributes are more common among churners compared to non-churners?
* Can churn be predicted using the available variables?
* What do the overall demographics of the bank's customers reveal?
* Are there differences in account behavior between German, French, and Spanish customers?
* What customer segments exist, and how can they be addressed strategically?
## Findings and Insights
### Churn Predictors:
Attributes like lower credit scores, younger age, lower account balance, fewer products, and inactivity were statistically significant among churners. Categorical variables such as geography and gender also showed significant churn patterns.

### Predictive Modeling:
A Random Forest model achieved an accuracy of 86.67%, with a notable area under the curve (AUC) score of 0.85. Significant features included activity level, balance, and number of products.

### Demographics:
Customers were predominantly middle-aged, with balanced representation across genders and geography. Specific segments displayed unique patterns in age, income, and activity levels.

### Geographical Differences:
Significant differences in account balances were observed between German, French, and Spanish customers, while other behaviors showed minimal variation.

## Customer Segments:

  * Cluster 0: Middle-aged, active, and financially stable customers.
* Cluster 1: Younger, disengaged but financially stable customers.
* Cluster 2: Moderate-balance customers with mixed activity and no credit cards.
* Cluster 3: Younger customers with low balances but high engagement.
## Summary
The project provided valuable insights into customer churn patterns and identified actionable segments within the bank's customer base. A predictive model was developed to foresee churn likelihood effectively, helping target vulnerable customers. Additionally, segmentation revealed distinct customer behaviors and needs, forming the basis for personalized interventions.

## Actions and Recommendations
### Retention Efforts:

* Target churn-prone customers (low activity, low balance) with personalized engagement plans.
* Offer rewards and incentives to active members to reinforce loyalty.
### Product-Specific Strategies:

* Introduce premium financial products to high-value customers (Cluster 0).
* Promote credit cards and investment plans for moderate-income groups (Cluster 2).
### Geographic Tailoring:

* Develop location-specific strategies, focusing on improving balances among German customers and engagement in France and Spain.
### Youth-Focused Initiatives:

* Educate younger customers (Cluster 3) on financial planning and introduce savings programs to improve balances.
### Data-Driven Monitoring:

* Regularly track key churn predictors and refine predictive models for proactive customer management.
