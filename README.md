# Customer Churn Analysis for Telecommunication Company

## Project Description
The goal of this project is to develop a machine learning model to predict customer churn for a telecommunications company. Churn refers to customers who stop using the company’s services. By identifying factors that influence churn, the company can develop strategies to retain customers, thus increasing revenue and profitability.

## Objective
- To understand the factors affecting customer churn.
- Understand the data and identify key factors that affect customer churn.
- Build and evaluate a classification model to predict churn.
- Provide actionable insights to the company to reduce churn rates.

## Data Sources
- **Training Data:** The first 3000 records accessed from a remote database.
- **Evaluation Data:** 2000 records from a GitHub repository.
- **Testing Data:** 2000 records from a OneDrive link.

## Hypotheses
- **Null Hypothesis (H0):** There is no significant relationship between the type of internet service (DSL, Fiber Optic, No) and customer churn.
- **Alternative Hypothesis (H1):** There is a significant relationship between the type of internet service (DSL, Fiber Optic, No) and customer churn.


## Business Questions

1. **What are the demographic characteristics of customers who are more likely to churn?**
   - I will explore the relationship between demographic variables (gender, senior citizen status, partnership status, dependents) and churn. For instance, are senior citizens more likely to churn than younger customers? Do customers with dependents churn at a different rate compared to those without?
 
2. **How does the tenure of a customer relate to their likelihood of churning?**
   - By analyzing the tenure column, I will determine if customers who have been with the company longer are more or less likely to churn. This analysis could reveal critical points in the customer lifecycle where churn is more likely, enabling targeted retention efforts.
 
3. **What role do service-related factors (e.g., internet service, tech support) play in customer churn?**
   - I will understand how the type and quality of services provided (internet service, online security, online backup, device protection, tech support, streaming services) impact churn. For example, does having multiple services reduce the likelihood of churn?
 
4. **How do different contract types and payment methods affect customer churn?**
   - I will examine the relationship between contract terms (month-to-month, one-year, two-year contracts), payment methods (electronic check, mailed check, bank transfer, credit card), and churn to provide insights into which contract types and payment methods are more stable.
 
5. **What is the relationship between monthly charges and total charges with customer churn?**
   - By analyzing the monthly charges and total charges, I will determine if higher or lower charges correlate with churn. This could indicate if pricing strategies need to be adjusted to retain customers.

## Methodology
The project follows the CRISP-DM framework:
1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Modeling**
5. **Evaluation**
6. **Deployment**

## Data Issues and Handling
- **Missing Values:** Imputation methods or dropping records.
- **Imbalanced Classes:** SMOTE or class weighting.
- **Outliers:** Statistical methods or transformations.
- **Data Format:** Standardization and consistent data types.

## Skills Developed
1. Data Exploration
2. Missing Value Computations
3. Feature Engineering
4. Creating Interactive Dashboards (Power BI/Tableau)
5. Building Machine Learning Pipelines (Logistic Regression, Decision Trees, Random Forest, etc.)
6. Model Evaluation and Interpretation (LIME, SHAP)
7. Model Optimization and Hyperparameter Tuning

## How to Use
1. Clone the repository.
2. Follow the instructions in the Jupyter notebook.
3. Ensure you have the required libraries installed.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Azubi Africa and Team
