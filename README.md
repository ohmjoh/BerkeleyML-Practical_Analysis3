# Bank Marketing Dataset Analysis

[Link to the Jupyter Notebook](https://github.com/ohmjoh/BerkeleyML-Practical_Analysis3/blob/main/Practical_Application_III.ipynb)

## Overview
This repo contains Practical Application 3 from Berkeley Engineering & Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence. 
This project analyzes a dataset related to marketing bank products over the telephone. The dataset is sourced from a Portuguese banking institution and contains the results of multiple marketing campaigns. The main objective is to understand the factors that influence a client's decision to subscribe to a term deposit and to visualize the relationships between various features and the target variable.

## Dataset
The dataset consists of various features related to the bank clients, the last contact of the current campaign, other attributes, and the output variable indicating whether the client subscribed to a term deposit.

### Features:
* Client Data:
  - Age
  - Job
  - Marital Status
  - Education
  - Default status
  - Housing loan status
  - Personal loan status
*Campaign Related:
  - Contact communication type
  - Last contact month
  - Last contact day of the week
  - Duration of the last contact
  - Number of contacts performed during this campaign
  - Number of days passed by after the client was last contacted from a previous campaign
  - Number of contacts performed before this campaign
  - Outcome of the previous marketing campaign
  - Social and Economic Context Attributes:
* Employment variation rate
  - Consumer price index
  - Consumer confidence index
  - Euribor 3 month rate
  - Number of employees
* Target Variable:
  - y: Whether the client subscribed to a term deposit (binary: 'yes', 'no')

## Objective
The primary objective of this analysis is to predict whether a client will subscribe to a term deposit based on the given features. This analysis can assist the bank's marketing team in targeting potential clients more effectively.

## Visualizations
The following visualizations were performed on the dataset:

- Distribution of Term Deposit Subscription: A count plot was used to visualize the distribution of the target variable 'y'.

- Continuous Variables: Box plots were used to visualize the distribution of each continuous variable against the target variable.

- Categorical Variables: Count plots were used to visualize the distribution of each categorical variable against the target variable.

## Conclusion
The analysis provides insights into the factors that influence a client's decision to subscribe to a term deposit. By understanding these factors, the bank's marketing team can devise strategies to target potential clients more effectively, thereby improving the success rate of their marketing campaigns.
