# Approved or Denied? <br> <sub> _An in-depth analysis on home loan application data_ </sub>
## Project Goal
The goal was to analyze home loan application data using visualizations and statistical modeling to derive insights on loan status based on borrower attributes. The outcomes are beneficial for individuals seeking to enhance their chances of securing a loan.

## Process
1. Leveraged Python to perform Exploratory Data Analysis on the [home loan data](data/loan_data.csv). Review the data cleaning and exploration process on [EDA.ipynb](notebooks/EDA.ipynb)
2. Modeled the [cleaned data](data/loan_data_cleaned_numeric.xlsx) using Logistic Regression and Random Forest Classifier to investigate the relationship between `Loan_Status` and the borrowers’ attributes. Evaluate the model results in [models.ipynb](notebooks/models.ipynb)
3. Explored further into the variables identified by Logistic Regression and Random Forest Classifier models as significant for determining loan status. Discover the steps involved in the variable reevaluation [post_model_EDA.ipynb](notebooks/post-model-EDA.ipynb)

## Model Results
* The Logistic Regression model identified credit history and marital status as the only statistically significant features.
* The Random Forest Classifier model identified credit history, applicant income, co-applicant income and loan amount as the top features that are the most influential to predicting loan status.
* Top 5 Features influencing Loan Status: Credit History, Applicant Income, Co-Applicant Income, Loan Amount and Marital Status.

## Recommendations
1. **Focus on Credit History:** Borrowers should ensure their credit history is positive and well-maintained as it’s a very important prerequisite to loan approval. Credit history has been identified as a prerequisite because merely having one does not guarantee automatic loan approval; this is where other aspects of the loan application process come into consideration.
2. **Consider Overall Financial Picture:** Borrowers should consider their overall financial situation when applying for loans as credit history is just one piece of the puzzle. Therefore, prospective borrowers should evaluate their overall financial health, including income, expenses, and debt, when applying for a loan.
3. **Proactive Improvement:** The most encouraging finding is that borrowers can directly influence the five most important features that would improve their chances of loan approval. Borrowers should take proactive steps to enhance these aspects within their control such as paying bills on time, seeking opportunities to boost income and responsible debt management.

## Challenges
* Interpreting the results in the presence of data imbalance.
* Identifying the most informative plots to extract insights from the dataset.
* Analyzing the feature importance in the presence of conflicting models' results.

## Future Goals
* Create and train a machine learning model that predicts the loan status based on a borrower’s application.
* Find additional data sources to enhance the level of detail in the dataset (e.g. credit score, debt-to-income ratio, employment history, etc.)





