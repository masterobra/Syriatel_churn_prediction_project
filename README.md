#  Syriatel Churn Prediction Project

##  Business Problem

Syriatel faces significant customer churn, threatening revenue and customer lifetime value. The goal is to predict churn and uncover the behavioral and service-related factors driving it. This enables targeted retention strategies and smarter resource allocation.



##  Project Objective

- Build and compare classification models to predict churn.
- Identify key features influencing customer decisions.
- Recommend actionable strategies based on model insights.



##  Models Compared

| Model                 | Accuracy | Precision | Recall  | F1-Score |
|----------------------|----------|-----------|---------|----------|
| Logistic Regression  | 0.859    | 0.533     | 0.891   | 0.338    |
| Random Forest (Tuned)| 0.898    | 0.581     | 0.639   | 0.492    |
| Decision Tree        | **0.917**| **0.693** | **0.692**| **0.692**|


##  Best Performing Model: Decision Tree

The Decision Tree model outperformed others across all metrics:

- **Accuracy**: 91.7% correctly predicted churn status.
- **Precision & Recall**: Balanced detection of churners and non-churners.
- **Interpretability**: Easy to visualize and explain to stakeholders.

This model is ideal for deployment in dashboards and churn monitoring systems.



##  Key Predictive Insights

- **Tenure ≤ 16.5 months** is the root churn condition.
- **Month-to-month contracts** and **high monthly charges** are strong churn signals.
- **Senior citizens** and **fiber optic users** show distinct churn patterns.



##  Recommendations

1. **Retention Campaigns**  
   Target customers with short tenure and high churn risk. Offer loyalty incentives or personalized outreach.

2. **Customer Support Improvements**  
   Reduce churn linked to frequent service calls by enhancing support quality and responsiveness.

3. **Flexible Pricing Plans**  
   Introduce tiered or bundled pricing to retain price-sensitive customers.

4. **Model Deployment Strategy**  
   Use the Decision Tree in real-time dashboards for churn alerts. Combine with human review for high-stakes decisions.



##  Limitations & Future Work

- Models may degrade over time without retraining.
- External factors (e.g., competitor actions) are not captured.
- Future work could explore ensemble methods or deep learning.









