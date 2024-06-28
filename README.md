# MOF-based Adsorption Refrigeration Cycle Analysis

## Project Overview

This project focuses on evaluating over 7000 Metal-Organic Frameworks (MOFs) for their suitability in an adsorption refrigeration cycle utilizing propane as the working fluid. The primary objective is to determine which MOFs exhibit the highest Coefficient of Performance (COP), indicating optimal efficiency in this application.

## Methodology

### Data Collection and Preparation
- **Dataset**: A comprehensive dataset comprising properties of 7000+ MOFs was collected. This includes structural, thermodynamic, and performance-related attributes relevant to their application in adsorption cycles.

### Model Training
- **Random Forest Regressor**: A machine learning model, specifically a Random Forest Regressor, was employed to predict COP values for each MOF based on its attributes. The dataset was split into training and testing sets, with a test size of 0.85 to ensure robust evaluation.

### Performance Evaluation
- **Pearson Matrix and R^2 Values**: A Pearson correlation matrix was computed to analyze the relationships between different attributes and COP values. R^2 values were calculated using three different cutoffs (0.2, 0.3, 0.5) to assess the model's predictive accuracy.

### Feature Importance
- **Gini Feature Importance**: Gini index-based feature importance was utilized to identify the most influential properties among the MOFs that significantly impact COP. This analysis helped prioritize which attributes contribute most to the performance of the adsorption cycle.

### Hyperparameter Tuning
- **GridSearchCV**: Hyperparameter tuning was performed using GridSearchCV to optimize the Random Forest model further. This iterative process involved selecting the most promising subset of MOFs (50 in this case) and adjusting model parameters to maximize predictive accuracy.

### Outcome
- The project culminated in the identification of top-performing MOFs based on their predicted COP values. Insights gained from the analysis contribute to the ongoing research and development of efficient adsorption refrigeration technologies.

## Conclusion

This project demonstrates the application of machine learning techniques and statistical analysis in evaluating MOFs for adsorption refrigeration cycles. By leveraging advanced modeling and evaluation methods, it aims to advance the understanding and application of MOFs in sustainable cooling technologies.
