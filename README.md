# *HR Analytics*

## Problem Statement

Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

## Features in Dataset

![hr](https://user-images.githubusercontent.com/94221244/151787938-663b6cc4-b881-4516-b960-bbe0655db056.png)

### Data Preprocessing 
1.Handled missing values by imputing with Median values
2.Segregated Numeric features,Categorical and Discreate features
3. Applied get_dummies() function on categorical and Discreate features.
### Hypothesis Testing
1.In order to get the importent features, I have used hypothesis testing such as ttest,Anova test,chi square test.
### Imbalanced Data treatment
1. I have used SMOTE over sampling technique in order to balance the data.
### Model building
I have used different models like 
- Logistic Regression
- Decision tree classifier
- Random forest classifier 
- Xgboost classifier
### Performance metrics
In order to evaluate model performence 
By evaluating performence metrics we got better Precision,Recall,F1 score in Xgboost classifier

### Test data evaluation
We have successfully predicted whether the employee is getting Promoted or not by using Xgboost classifier.











