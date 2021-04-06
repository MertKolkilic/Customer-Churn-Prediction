# Customer Churn Prediction
Customer is one of the most valuable resources in any business, acquiring customers can be time consuming and expensive. Retaining the most profitable customers can be one of the best strategies businesses can have. It will be very important to identify customers before they leave. Churn analysis was very useful in Data Science.
Business or organizations are interested in knowing the set / segment / group of customers who want to leave. Retention is more cost effective than acquiring a new customer. There is always a cost and risk to acquiring a new customer. Below is an example of churn analysis and Applied Machine Learning in a telecom customer dataset.
# Data
The dataset comes from the Kaggle, and it is related to Telecom clients. The classification goal is to predict whether the client will churn (1) or stay (0).
# Input Variables
"state", string. 2-letter code of the US state of customer residence.

"account_length", numerical. Number of months the customer has been with the current telco provider

"area_code", string="area_code_AAA" where AAA = 3 digit area code.

"international_plan", . The customer has international plan.

"voice_mail_plan", . The customer has voice mail plan.

"number_vmail_messages", numerical. Number of voice-mail messages.

"total_day_minutes", numerical. Total minutes of day calls.

"total_day_calls", numerical. Total minutes of day calls.

"total_day_charge", numerical. Total charge of day calls.

"total_eve_minutes", numerical. Total minutes of evening calls.

"total_eve_calls", numerical. Total number of evening calls.

"total_eve_charge", numerical. Total charge of evening calls.

"total_night_minutes", numerical. Total minutes of night calls.

"total_night_calls", numerical. Total number of night calls.

"total_night_charge", numerical. Total charge of night calls.

"total_intl_minutes", numerical. Total minutes of international calls.

"total_intl_calls", numerical. Total number of international calls.

"total_intl_charge", numerical. Total charge of international calls

"number_customer_service_calls", numerical. Number of calls to customer service

# Predict variable (desired target):
"churn", . Customer churn.
# Data Preprocessing
I have used pandas for data preprocessing, the data set came with column labels and each row represents single client data. In terms of missing values or duplicates (a rare case in real-world data) came pretty clean.
besides python, pandas, and sk-learn, Excel & Tableau public is being used for this end to end project
