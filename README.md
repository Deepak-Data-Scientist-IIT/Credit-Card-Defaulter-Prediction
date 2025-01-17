App - https://credit-card-defaulter-6.herokuapp.com/


Credit-Card-Default-Prediction

Overview
This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers.

Motivation
There are times when even a seemingly manageable debt, such as credit cards, goes out of control. Loss of job, medical crisis or business failure are some of the reasons that can impact your finances. In fact, credit card debts are usually the first to get out of hand in such situations due to hefty finance charges (compounded on daily balances) and other penalties.

A lot of us would be able to relate to this scenario. We may have missed credit card payments once or twice because of forgotten due dates or cash flow issues. But what happens when this continues for months? How to predict if a customer will be defaulter in next months?

To reduce the risk of Banks, this model has been developed to predict customer defaulter based on demographic data like gender, age, marital status and behavioral data like last payments, past transactions etc.

Dataset Information
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

Technical Aspect
This project is divided into two part:

Training a RandomForestClassifier classification model to predict defaulter as accurate as possible.
Cleaning the datasets, fixing all features
Apply Classification ML model
Building and hosting a Flask web app on Heroku.
Build the web app using Flask API
Upload the project on GitHub
Get the customer information from Web app
Display the prediction
Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt
Directory Tree
├── templates 
│   └── index.html
├── app.py
├── credit-card-default.csv
├── credit card default.ipynb
├── model.pkl
├── Procfile
├── README.md
├── Detailed Description Presentation
├── README.md
└── requirements.txt# Credit-Card-Defaulter-Prediction

