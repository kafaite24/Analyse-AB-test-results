# Analyse-AB-test-results

## Introduction 

A/B tests are very commonly performed by data analysts and data scientists.

Our goal of this project is to understand the results of an A/B test run by an e-commerce website and to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

There are 3 parts of this project:

### 1- Probability

Statistics were used to find out the probabilities of converting regardless of the page which were then used to analyze if the new or old page led to more conversions.

### 2- A/B test

Hypothesis testing was done with the null hypothesis that the old page is better or equal to the new page unless with sufficient evidence we can prove that the new page is to better at a Type I error rate of 5%.The data was bootstrapped and sampling distributions were made for both pages and then conclusions were drawn based on the p-values.

### 3- Regression Approach

Logistic regression was performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.
Another factor, country a user lives in, was also added to see if it impacts the results. 

## Tools

Python3

Jupyter Notebook

Numpy, Pandas, Matplotlib, StatsModels, Scipy

**Note: You can find the attached .ipynb and Html file and the required dataset files as, 'ab_data.csv' and 'countries.csv'**

