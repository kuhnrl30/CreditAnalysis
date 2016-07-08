Credit Approval Analysis
========================================================
author: Ryan Kuhn
date: May 1, 2015

Background
========================================================

**Objective:** To demonstrate the analytical techniques taught during the Special Topics in Audit Analytics course at Rutgers University

**Data Source:** UCI Machine Learning Repository

**Assumptions:** Field names and values changed to meaningless values. 
Made assumtions about what attributes the data represents.

Research Questions
========================================================

**Q:**  Is there a correlation between Age, Income, Credit Score, and Debt levels and the credit approval status? 
Can this relationship be used to predict if a person is granted credit? 
If yes, does the relationship indicate reasonable risk management strategies?

Research Question - 1
========================================================

**Q:**  Is there a relationship between Age, Income, Credit Score, and Debt levels and the credit approval status? 
Can this relationship be used to predict if a person is granted credit? 
If yes, does the relationship indicate reasonable risk management strategies?

**A:** Correlation exists between Prior default, Years employed, Credit score, and Income level. 
These variables are reasonable management strategies. 


Research Question- 2
========================================================

**Q:** Ethnicity is a protected status and the decision to approve or deny an application cannot be based on the applicant's ethnicity.  
Is there a statistically significant difference in how credit is granted between ethnicities that could indicate bias or discrimination? 

**A:**  A chi-squared test did not give evidence that ethnicity and approval status are dependent. 

Analytic Methods Used
========================================================

Methods used: 

- Linear regression 
- Descriptive Statistics and Normalization
- Association Rules 
- Logistic regression
- Classification and Regression Tree
- Ensembling

Linear Regression
========================================================

