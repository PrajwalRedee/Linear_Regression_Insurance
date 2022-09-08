

# Predicting annual medical expenditure for new customers

QUESTION: ACME Insurance Inc. offers affordable health insurance to thousands of customer all over the United States. As the lead data scientist at ACME, you're tasked with creating an automated system to estimate the annual medical expenditure for new customers, using information such as their age, sex, BMI, children, smoking habits and region of residence.

You're given a CSV file containing verified historical data, consisting of the aforementioned information and the actual medical charges incurred by over 1300 customers.
## Dataset

url =  'https://raw.githubusercontent.com/JovianML/opendatasets/master/data/medical-charges.csv'

The dataset can be downloaded from the above url.
## Roadmap

- Exploratory Data Analysis and Visualization
- Analyzing target variable with other features
- Correlation between the features
- Linear Regression using single feature
- Converting categorical column into numeric and using that in the model training
- Feature Scaling
- Training the model using Test and Train data set



## Summary

* I evaluated the model by using Root Mean Sqaured Error

```bash
  Test Set Loss: 5639.157742766675
```

```bash
  Training Set Loss: 6086.804021239969
```
