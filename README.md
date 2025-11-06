# Bank Customer Churn Prediction Using CHAID Decision Tree in IBM SPSS Modeler

## Overview
This project predicts bank customer churn using the CHAID (Chi-squared Automatic Interaction Detection) decision tree algorithm in IBM SPSS Modeler. It analyzes customer demographics, tenure, and financial behavior to identify key drivers of churn and assist banks in developing effective customer retention strategies.

## Problem Statement
In the modern banking industry, customer retention is one of the most pressing challenges. 
With the rapid digital transformation of financial services and the increasing number of 
competitors offering similar products, customers can easily switch banks in search of better 
rates, convenience, or service quality. This phenomenon, known as customer churn, directly 
impacts a bank’s revenue, profitability, and brand trust. Acquiring a new customer often costs 
several times more than retaining an existing one, making churn prevention both a strategic 
and financial necessity.

## Objective
To build and evaluate a CHAID decision tree model that:
- Classifies customers as likely to churn or stay.
- Identifies key churn predictors.
- Provides interpretable decision rules for actionable business insights.

## Dataset
**Source:** [Kaggle – Bank Customer Churn Data](https://www.kaggle.com/datasets/pentakrishnakishore/bank-customer-churn-data)

**Key Attributes:**
- Demographics: Age, Gender, Occupation, City  
- Account Tenure: Account vintage (years)  
- Financial Data: Balance, Net Worth, Credit Score  
- Behavioral Data: Monthly transactions, Product usage  
- Target: Churn (Yes/No)

## Tools and Technologies
- IBM SPSS Modeler – for data modeling and visualization  
- CHAID Algorithm – for decision tree-based classification  
- Kaggle Dataset – real-world banking churn data  
- MS Excel / CSV – for data preprocessing

## Methodology
1. **Data Import:** Loaded dataset into IBM SPSS Modeler and verified column integrity.  
2. **Data Preparation:** Cleaned and standardized data, handled missing values.  
3. **Variable Assignment:** Defined churn as the target variable and assigned predictor roles.  
4. **Model Configuration:** Set CHAID parameters including significance level and maximum tree depth.  
5. **Model Execution:** Trained the CHAID model and generated decision tree outputs.  
6. **Result Interpretation:** Analyzed node splits and extracted churn-related business rules.

## Results
- Key churn predictors: Account tenure, balance, transaction frequency, and age.  
- CHAID model provided interpretable segmentation with clear decision rules.  
- Findings enable targeted retention actions and reduced attrition costs.

## Conclusion
The CHAID decision tree effectively identifies customer segments with higher churn likelihood. By applying this model, banks can proactively implement retention strategies, reduce acquisition costs, and improve overall profitability through data-driven insights.

![IBM SPSS Modeler Stream Preview](asset/Screenshot%202025-10-28%20003500.png)

### IBM SPSS Modeler Stream Preview

The image above provides a preview of the workflow built in IBM SPSS Modeler to predict bank customer churn using the CHAID (Chi-squared Automatic Interaction Detection) algorithm. It visually represents the data preparation, model building, and evaluation steps involved in the analysis.

The flow includes:
- Data import from the `churn_prediction.csv` file.
- Processing of customer demographics, financial data, and churn flags.
- Application of the CHAID decision tree algorithm to segment customers based on churn likelihood.
- Evaluation of model performance through various aggregated results.


## Future Work
- Compare CHAID performance with advanced algorithms (Random Forest, XGBoost).  
- Integrate results into a real-time churn prediction dashboard.  
- Include sentiment analysis and behavioral data for improved model accuracy.  
- Automate retention campaign recommendations.

## Project Structure
```
bank-customer-churn-prediction-chaid-spss/
│
├── asset/
│   └── screenshot.png               # Stream screenshot
├── bank_customer_churn.pdf          # Detailed workflow and results
├── PROBLEM STATEMENT.pdf            # Problem background
├── dataset.csv                      # Input dataset (from Kaggle)
├── stream                           # IBM SPSS Modeler stream (CHAID model workflow)
└── README.md                        # Project documentation
```

## Author
**Akbar Naeem**  
*Babu Banarasi Das University*  
*Supervisor: Mr. Vikas Kumar*
