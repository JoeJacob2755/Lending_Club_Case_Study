# Lending Club Case Study
> Lending Club Data Analysis: A Case Study.


## Table of Contents

- 1.Introduction
  - 1.1 Data Set Description
  - 1.2 Bussiness Understanding
- 2.Bussiness Objective
- 3.Project Approch
- 4.Importing Libraries and Packages
- 5. Creating Custom Functions
- 6. Data Loading
- 7. Data Description
  -7.1 Observations
- 8. Data Cleaning
  - 8.1 Missing Values
    - 8.1.1 Observations
  - 8.2 Examine Balance Columns
    - 8.2.1 Employee Title
    - 8.2.2 Employee Length
    - 8.2.3 Description
    - 8.2.4 Title
    - 8.2.5 Revolving Credit Utilisation
    - 8.2.6 Last Payment Date
    - 8.2.7 Last Credit Pull Date
    - 8.2.8 Collections Last 12 Months
    - 8.2.9 Charge Off in LAst 12 Months
    - 8.2.10 Public Recorded Bankruptcies
    - 8.2.11 Tax Liens
  - 8.3 Dropping Columns and Rows with Missing Values
- 9.Unique Values
- 10. Dealing with Redundant Data
- 11. Dealing with Dates
- 12. Correcting Data Types
- 13. Outlier Detection and Removal
- 14. Creating Bins for Contionus Data
- 15. Analysing Each Col for Discripencies
  - 15.1 Column Analysis
  - 15.2 Distribution of Column Values
    - 15.2.1 Data Distribution Part - I
    - 15.2.2 Data Distribution Part - II
    - 15.2.3 Data Distribution Part - III
- 16. Univariate Analysis
  - 16.1 Analysis of Variables aganist Loan Status
  - 16.2 Univariate Analysis aganist Deafaulted Loan Percentage
- 17. Bivariate Analysis
- 18 Conclusion
  - 18.1 Summary
  - 18.2 Recommendations
- 19.Acknowlegement

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is a loan provider and also works as a peer to peer lending enable.
- This project is done to enable Lending Club to analyise the loan applicants to see the possibility of default
- Bussiness Objective: What are the factors that incluence the chances of loan default
- Dataset being used is 'loan.csv' provided by UpGrand and III-T Banglore
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Though a large number of features were present in the initial data set, most of the data were redundant and not good for the analysis.
- Cleaning of the data and removing redundant data brought the features by more than 50%.
- Recommendations
  - The best driving features for the Loan default analysis are:
  - Interest Rate : Higher interest rare leads to more defaults
  - Term : Lower terms means larger instalments and hence more chances of defaults, unless borrower is interested in earlier payback.
  - Grade : Better the grade lower the chances of default
  - Purpose : Payment towards already existing debts are likely to end in default.
  - Revolving Credit Utilisation : Higher utilisation of revolving credit may lead to defaults as the borrower's financial ability to   service the loan become lesser due to existing liabilities.
  - Instalment : Higher the instalment, more chances of default
  - Annual Income : Lower the income, chances to default are more. Also, see this in relation with existing credit because high income people with high liabilities can also be defaulters.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - python  version 3.6
- library - pandas  ver 1.3.5
- library - numpy   ver 1.21.5
- librabry - matplotlib
- librabry - seaborn
- librabry - datetime


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any Kaggle and Github
- This project was based on [Module 2: EDA](https://www.example.com).


## Contact
Created by [@JoeJacob2755] - feel free to contact me!

