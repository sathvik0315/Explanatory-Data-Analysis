# Explanatory-Data-Analysis

- This project, led by me, is a mini college project aimed at performing explanatory data analysis using a dataset from Kaggle focused on an online retail company based in the United Kingdom.

## Overview
🌟 The full form of EDA means Explanatory Data Analysis.  
🌟 It is a process of performing initial investigations on data.  
🌟 By doing this kind of analysis, it helps us to discover patterns and standards.  
🌟 It clearly explains the summary of statistics and graphical representations.  

### Dataset
- e-Commerce domain
- The dataset consists of transactional data with customers indifferent countries who make purchases from an online retail company based in the United Kingdom (UK).
- Company: UK-based and online retail
- Products for selling: Mainly all-occasion gifts
- Customers: Most are wholesalers (local or international)
- Transactions Period Data : From 1st Dec 2010 to 9th Dec 2011 (One year)
- 
## Dataset Explanation
✔ InvoiceNo (invoice_num): A number assigned to each transaction  
✔ StockCode (stock_code): Product code  
✔ Description (description): Product name  
✔ Quantity (quantity): Number of products purchased for each transaction  
✔ InvoiceDate (invoice_date): Timestamp for each transaction  
✔ UnitPrice (unit_price): Product price per unit  
✔ CustomerID (cust_id): Unique identifier for each customer  
✔ Country (country): Country name
### File Structure

```python
import pandas as pd
import numpy as np
import warnings
import matplotlib.pyplot as plt
import seaborn as sns
# ... (rest of the code)
```

- eda_analysis.py: Python script for performing explanatory data analysis.
- data.csv: CSV file containing the dataset from Kaggle.
- visualizations.py: Script to generate pie charts, bar graphs, and other visualizations.
- requirements.txt: List of dependencies for installing required libraries.

## Results from EDA

🌟 Highest Number of Orders from Specific Country  
💰 Highest Money Spent on Purchases from Specific Country  
🌍 Top 5 Countries by Number of Orders  
💵 Top 5 Countries by Money Spent on Purchases  
📅 Highest Sales in a Specific Month  
📉 No Transactions Between Certain Dates  
📈 Days with Increasing Sales  
📉 Days with Decreasing Sales  
⏰ Hours with the Highest Number of Orders  

## Contribution 

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.  











