# Telco Customer Churn Analysis

### Company Background:

Saudi Telecom Company (STC) is a Saudi Arabia-based digital company that offers telecommunications services, landline, mobile, Internet services, enterprise digital solutions, entertainment, fintech, and computer networks

### Motivation:
STC has a problem with retaining its customers due to new competitors emerging in the market (Virgin, Mobily, etc..) so we will try to offer some analysis to diagnosis the behavior of the churned customers so that we can first address these problems as organizational challenges to improve our services as well as identify common behaviors in churned customers

### Data Description

>I will be using the Telco Customer Churn “Focused customer retention programs” Dataset from Kaggle that can be found [here](https://www.kaggle.com/blastchar/telco-customer-churn).
This was uploaded for examining customer retention and predicting churn and will be well suited to this study

The data contains more than **7043** row each row represents a customer and **22** features included in our analysis.
#### Features
>- customerID: A unique identifier for each cutomer
>- gender: Whether the customer is a male or a female
>- SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
>- Partner: Whether the customer has a partner or not (Yes, No)
>- Dependents: Whether the customer has dependents or not (Yes, No)
>- tenureNumber of months the customer has stayed with the company
>- PhoneService: Whether the customer has a phone service or not (Yes, No)
>- MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
>- InternetServiceCustomer’s internet service provider (DSL, Fiber optic, No)
>- OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
>- OnlineBackup: Whether the customer has online backup or not (Yes, No, No internet service)
>- DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
>- TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
>- StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
>- StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
>- ContractThe contract term of the customer (Month-to-month, One year, Two year)
>- PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
>- PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
>- MonthlyCharges: The amount charged to the customer monthly • TotalCharges`: The total amount charged to the customer
>- Churn: Whether the customer churned or not (Yes or No)
An imbalance can be observed in the target label as the number of lost customers are 1890 rows while the number of non-churn customers are 5174 rows


