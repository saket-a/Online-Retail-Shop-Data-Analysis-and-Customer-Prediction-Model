# Online-Retail-Shop-Data-Analysis-and-Customer-Prediction-Model
This project involves the data analysis and a simple prediction model of a dataset of an online retail shop.

This project has two major objectives:
1. Data analysis and classification after feature engineering
2. Revenue prediction model

All implementation files and dataset has been uploaded in the repository.

### Technology Stack
**IDE:** Jupyter Notebook (Anaconda)\
**Packages used:**
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- sklearn
- pickle
- flask

### File Description
- classification.ipynb : This file involves data analysis and feature engineering and, at the end classifies the customers into 3 segments - low, high and mid-value, based on important features - Recency, Frequency and Revenue.
- main.ipynb and app.ipynb : These files are used in building the prediction model that classifies the orders in 3 groups of revenue.
- model.pkl : The pickle model file generated from the app.ipynb file.
- templates/index.html: HTML file for the predictor model. Used as the front end for user.
- Online Retail.csv : Dataset

### Dataset
The dataset *Online Retail* is a CSV file having following columns/attributes.
- InvoiceNo: Invoice number of the order
- StockCode: Product code
- Description: Product description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

### Use Case
1. The classification model can be used to predict the value of customers. This insight can be used for purposes like target marketing.
2. The prediction model can be used to predict where a new order fits in the revenue groups. It work for both existing and new customers.

### Machine Learning models
1. Classification - Random Forest Classifier
2. Presiction model - K-Means Classifier
