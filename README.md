# Machine Learning; Final Project; Coursera

## Classification with Python

In this notebook we try to practice the classification algorithms: 

- K Nearest Neighbor(KNN)

- Decision Tree

- Support Vector Machine

- Logistic Regression

Load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

The metrics used to report the accuracy of each classifier:

- Jaccard index

- F1-score

- LogLoss

#### About dataset

This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:


| Field | Description |
|---|---|
|Loan_status |Whether a loan is paid off on in collection
|Principal |Basic principal loan amount at the
|Terms |Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule
|Effective_date	 |When the loan got originated and took effects
|Due_date	|Since it’s one-time payoff schedule, each loan has one single due date
|Age |Age of applicant
|Education |Education of applicant
|Gender	|The gender of applicant
