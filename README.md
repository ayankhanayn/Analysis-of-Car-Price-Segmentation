# Predictive Analysis of Car Price Segmentation Using SPSS


## Overview
This project used IBM SPSS Modeler 18.6 to build a CHAID (Chi-squared Automatic Interaction Detection) Decision Tree on car sales data. The model achieved 94.27% Overall Accuracy in predicting the "High Price" segment (defined by the 75th percentile), confirming Mileage as the most significant factor.

## Problem Statement
The used car market lacks an objective, data-driven methodology to accurately classify vehicles into high-value and standard-value segments. Without this clarity, businesses struggle with optimal pricing, inventory management, and targeted marketing of premium stock. 

## Objective
To identify which car attributes (like Mileage, Engine Size, and Year) are the most significant drivers of high market value, achieving a reliable price prediction model.

## Dataset
**Source:** [Kaggle – Global Car Sales Data](https://www.kaggle.com/code/devraai/global-car-sales-data-analysis-and-modeling/input?select=car_sales_data.csv)

## Tools and Technologies
- IBM SPSS Modeler – for data modeling and visualization  
- CHAID Algorithm – for decision tree-based classification  
- Kaggle Dataset – global car sales dataset  
- MS Excel / CSV – for data preprocessing

## Methodology
1. **Data Understanding and Preparation:** Loaded dataset into IBM SPSS Modeler and verified column integrity.  
2. **Data Transformation and Feature Engineering:** Target Creation and Field Filtering.  
3. **Modeling and Validation Setup:** Partioning.  
4. **Model Building:** Set CHAID parameters including significance level and maximum tree depth.  
5. **Evaluation and Visualization:** Performance Assessment and Model Interpretation.  

## Conclusion
The CHAID model achieved high overall accuracy (94.27%). While it is slightly better at identifying 'Standard Price' cars (96.80\%), it still has a very strong 86.30% success rate in correctly identifying the target 'High Price' segment. This demonstrates that the features selected by the model are highly effective at differentiating high-value vehicles.

![IBM SPSS Modeler Stream Preview](asset/Screenshot%202025-11-06%20123416.png)

## Project Structure
```
Analysis-of-Car-Price-Segmentation/
│
├── asset/
│   └── screenshot.png               # Stream screenshot
├── Final_P.pdf                      # Detailed workflow and results
├── PROBLEM STATEMENT.pdf            # Problem background
├── dataset.csv                      # Input dataset (from Kaggle)
├── Final_P_stream                   # IBM SPSS Modeler stream (CHAID model workflow)
└── README.md                        # Project documentation
```

## Author
**Ayan Khan**  
*Babu Banarasi Das University*  
*Supervisor: Mr. Robin Tyagi*
