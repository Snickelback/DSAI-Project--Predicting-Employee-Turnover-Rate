# DSAI Project: Predicting-Employee-Turnover-Rate

## About

This is our SC1015 DSAI Mini Project titled Predicting Employee Turnover Rate.

Employment Turnover Rate is a measurement of how many employees leave an organisation over a specific period of time. Their withdrawal from the organisation could be caused by many factors and it could be voluntary or involuntary. A voluntary turnover is where employees choose to leave their organisation and it could be due to stress, an unfavourable working environment in the company or personal reasons. An involuntary turnover on the other hand is where employers choose to terminate employees, and this could be due to the employee’s inadequacy or employers trying to cut costs. We wish to focus on the voluntary employee turnover rate, as it would be a very useful “marker” and indicator for employers. With an awareness of the voluntary employee turnover rate, employers would get a better sense of how happy or satisfied their employees are while working for them, and they can act on the problem should the predicted rate be very high.


## Problem definition

- What are the most effective variables in predicting employee turnover rate?
- Can we come up with a model to predict employee turnover using a combination of these factors?

## Dataset used
The dataset used for this project is retrieved from [here](https://www.kaggle.com/datasets/rohitsahoo/employee?resource=download)


## Presentation
The presentation slides and video are attached above.

## Brief process walkthrough

1. Data Preparation & Cleaning
   - Check for empty values or duplicate values
   - Encoding Categorical Variables using Label Encoding
   
2. Exploratory Data Analysis
   - Box Plot
   - Histograms
   - Violoin Plots
   
3. Machine Learning
   - Logical Regression Model
   - Random Forest Classifier

5. Conclusions

## Conclusions
Our ML models Logistic Regression and Random Forest helped us establish a great way to predict the employer turnover rate. The Logistic Regression model was particularly effective in establishing the variables that were key in predicting the turnover rate. They are the 5 we identified:
- Overtime
- EnvironmentSatisfaction
- YearsSinceLastPromotion
- YearsAtCompany
- TotalWorkingYears

However, the accuracy of the model is certainly of concern. On the other hand, the random forest model is much more accurate and effective in predicting the turnover rate.

The variables identified are definitely not the only ones that result in signoificant employee turnovers; there exist other variables too that we could not explore here in this dataset. Yet, this model provides a good start with particularly helpful information to ensure that turnover rates can be kept to a minimum.


## Key learning points
- Label Encoding for categorical variables
- Logistic regression model training & evaluation
- Random Forest Classifier Model


## Contributors

1. @snickelback (Nithin Raj Murali Babu)
2. @_____ (Ke Nora)

## References

- https://www.kaggle.com/datasets/HRAnalyticRepository/employee-attrition-data?datasetId=656&language=Python
- https://www.kaggle.com/code/gauri1996/employeeattritionrate-analysis-modelling#Read-dataframe-&-analyzing-it
- https://www.kaggle.com/code/aradhanapratap/employee-attrition-eda-7-classifier-evaluations#kln-196
