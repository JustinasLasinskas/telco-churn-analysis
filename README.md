# Telco Customer Churn Analysis

Classification analysis using Kaggle's Telco Customer Churn dataset.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Data](#data)
- [Methods](#methods)
- [License](#license)

## Project Description

The project includes:

- Explanatory data analysis, also known as EDA;
- Data wrangling;
- Feature selection;
- Modelling.

## Installation

### Clone the repository:

`git clone https://github.com/your-username/your-repo.git`

### Navigate to the project directory:

`cd your-repo`

### Create a virtual environment (optional but recommended):

`python -m venv venv`  
`source venv/bin/activate # For Linux/Mac`  
`venv\Scripts\activate # For Windows`

### Install the required packages

`pip install -r requirements.txt`

## Data

Data is based on Kaggle Telco Customer Churn dataset, which can be found @ https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### data Attributes

- **customerID** - Customer ID
- **gender** - Whether the customer is a male or a female
- **SeniorCitizen** - Whether the customer is a senior citizen or not (1, 0)
- **Partner** - Whether the customer has a partner or not (Yes, No)
- **Dependents** - Whether the customer has dependents or not (Yes, No)
- **tenure** - Number of months the customer has stayed with the company
- **PhoneService** - Whether the customer has a phone service or not (Yes, No)
- **MultipleLines** - Whether the customer has multiple lines or not (Yes, No, No phone service)
- **InternetService** - Customer’s internet service provider (DSL, Fiber optic, No)
- **OnlineSecurity** - Whether the customer has online security or not (Yes, No, No internet service)
- **OnlineBackup** - Whether the customer has online backup or not (Yes, No, No internet service)
- **DeviceProtection** - Whether the customer has device protection or not (Yes, No, No internet service)
- **TechSupport** - Whether the customer has tech support or not (Yes, No, No internet service)
- **StreamingTV** - Whether the customer has streaming TV or not (Yes, No, No internet service)
- **StreamingMovies** - Whether the customer has streaming movies or not (Yes, No, No internet service)
- **Contract** - The contract term of the customer (Month-to-month, One year, Two year)
- **PaperlessBilling** - Whether the customer has paperless billing or not (Yes, No)
- **PaymentMethod** - The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **MonthlyCharges** - The amount charged to the customer monthly
- **TotalCharges** - The total amount charged to the customer
- **Churn** - Whether the customer churned or not (Yes or No) - TARGET VARIABLE

## Methods

The project used various classfication methods used in the analysis, such as **Logistic Reggresion**, **KNN**, **XGBoost**, **CatBoost**, **LightGBM**, **AdaBoost Model**, **Gradient Boosting Model**, **ANN** and other.

## License

**MIT License**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
