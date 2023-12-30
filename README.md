# LP2-Classification-Project
A Machine Learning project that analyzes a Telco churn data to train our program and help answer a few questions. Churn rate in this case means the rate at which customers leave or stop using a company's products and services. The main goal is to determine what percentage of customers leave and ideally the factors that contribute to the churn. The end goal is to improve customer retention by analyzing the factors contributing to the churn rate.


## Features Explanation:

 The following describes the columns present in the data.

* Gender -- Whether the customer is a male or a female
* SeniorCitizen -- Whether a customer is a senior citizen or not
* Partner -- Whether the customer has a partner or not (Yes, No)
* Dependents -- Whether the customer has dependents or not (Yes, No)
* Tenure -- Number of months the customer has stayed with the company
* Phone Service -- Whether the customer has a phone service or not (Yes, No)
* MultipleLines -- Whether the customer has multiple lines or not
* InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)
* OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)
* OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)
* DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)
* TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)
* StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)
* Contract -- The contract term of the customer (Month-to-Month, One year, Two year)
* PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)
* Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))
* MonthlyCharges -- The amount charged to the customer monthly
* TotalCharges -- The total amount charged to the customer
* Churn -- Whether the customer churned or not (Yes or No)    

# HYPOTHESIS:
* Null Hypothesis: Customer Gender does not affect the churn rate
* Alternate Hypothesis: Customer Gender contributes to churn rate

# QUESTIONS:
1) Does age factor affect the customers churn rate?
2) Among customers who have churned, which type of contract is most prevalent?
3) Which gender has the higest rate of churning
4) What is the percentage breakdown of customers who have left the company? (Pie chart)
5) Is there a correlation between total charges and the type of contract? (Bar chart)
6) How does the churn rate vary based on the duration of customer subscription (tenure)?

Outline:

Business Understanding:

    1)  Explanation of features
    2)  Hypothesis (Null and Alternate)
    3)  Analytical questions
Data Understanding:

    1) Importation
    2) Load Dataset
    3) EDA
    4) Answer Analytical questions
    5) Test Hypothesis
    6) Give your insights
Data Preparation:

    1) Split data into X,y
    2) Pipeline Creation
    3) Encode
    4) Split data into training and testing
    
Modelling and Evaluation:

License:

MIT

References:

* https://scikit-learn.org/
* Pandas documentation
* W3Schools
* simplilearn.com/tutorials/machine-learning-tutorial/classification-in-machine-learning
* analyticsvidhya.com/blog/2022/07/step-by-step-exploratory-data-analysis-eda-using-python/