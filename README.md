# Fraud Analysis

## Description
This project focuses on analyzing mobile money transactions to identify fraudulent activities using the PaySim dataset. The dataset is a synthetic simulation based on real financial logs from a multinational financial service provider operating across 14 countries.

## Dataset Overview
The PaySim dataset contains a scaled-down version (1/4th of the original size) of mobile transaction logs. It provides data points such as transaction types, amounts, and whether a transaction was flagged as fraudulent.

### Key Features:
- **Synthetic Data**: Simulated data ensures privacy while maintaining statistical integrity.
- **Transaction Types**: Includes multiple transaction categories.
- **Target Variable**: Flag indicating whether a transaction is fraudulent.

## Methodology

### Hypothesis Testing
Performed the following statistical tests to analyze transaction patterns and fraud detection:
- **Chi-Square Test**
- **T-Test**
- **Mann-Whitney U Test**
- **ANOVA Test**

### Machine Learning Models
Implemented various models to predict fraudulent transactions:
- Logistic Regression
- Decision Tree Classifier
- Linear Discriminant Analysis
- Gaussian Naïve Bayes
- Support Vector Machine
- K-Nearest Neighbors Classifier

#### Handling Imbalanced Data
- **Under-sampling**: Applied to balance the dataset and improve model performance.

### Tools and Libraries
- **Visualization**: Tableau
- **Statistical Tests**: Scipy, Statsmodels

## Results and Insights
- **Hypothesis Testing**: Identified significant patterns and associations between transaction categories and fraudulence.
- **Machine Learning Models**: Demonstrated varying accuracy levels, with each model providing unique insights into fraud detection.


## Visualization: Tableau
[Link](https://public.tableau.com/views/FraudAnalysis_17346286812220/Dashboard13?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Trello:
[Link](https://trello.com/b/cleZOnux/fraud-analysis-project)
