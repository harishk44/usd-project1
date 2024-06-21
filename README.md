***Customer Churn Prediction Project***

***Introduction***

  In the telecom sector, customers have the flexibility to select from various service providers, often switching between them. 
  This results in a substantial annual churn rate of 15-25% in this fiercely competitive market. 
  As retaining a customer costs is significantly less than acquiring a new one (five to ten times less) customer retention 
  has become a priority over acquisition. 
  
  For established telecom companies, the primary business objective is keeping their most profitable customers. 
  To minimize churn, it is crucial for these companies to identify which customers are likely to leave.
  In our project, we will analyze customer data from a leading telecom company, develop models to predict potential churn, 
  and pinpoint the key predictors of churn.

  Churn can be defined in several ways in the telecom industry:

   Revenue-based churn: 
     Customers who have not engaged in any revenue-generating activities like using mobile internet, making outgoing calls, or sending SMS 
     over a certain period.

   Usage-based churn: 
     Customers who have neither incoming nor outgoing usage—calls, internet, etc.—over a designated period. 
     A drawback of this approach is that identifying churn based on a prolonged period of inactivity, such as two months, 
     might be ineffective as the customer may have already switched providers by the time they are flagged.

  In this project, we will adopt the usage-based method to identify churn based on the data collected from the telecom industry in Iran. We will delve into how predicting and managing churn can benefit telecom companies.
  The dataset is randomly collected from an Iranian telecom company database over a period of 12 months. A total of 3150 rows and 13 columns of data, each row representing the customer information. The attributes that are in this       dataset are called out below. All of the attributes except for attribute churn is the aggregated data of the first 9 months.The churn labels are the state of the customers at the end of 12 months. The three months is the designated   planning gap.

***Project Objective***

  The primary objectives of this project are:

    Understand the Modeling process: Understanding the different steps involved in the process of machine learning modeling

    Model Selection: Experiment with different statistical and machine learning models and decide the best model for this use case

    Launching pad for future projects: Use this project as a stepping stone for applying the lessons learnt for future projects

***Project Contents***
  This repository includes:
  
    Jupyter Notebook with code covering the following areas of modeling
    
      Introduction
      Data Cleaning/Preparation
      Exploratory Data Analysis
      Model Selection
      Model Analysis
      Conclusion and Recommendations.
    
***Dependencies***
    To run the code and experiments in this project, you'll need the following libraries and dependencies:

      python (version 3.X)
      numpy
      pandas
      plotly
      matplotlib
      sklearn
      xgboost
      imblearn
      
      You can install these dependencies using pip or another package manager.
        pip install numpy
