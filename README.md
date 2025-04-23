Regulations guiding data information

The Data Protection Act (DPA) establishes rules for the collection, storage, processing, and use of personal data by organizations. Its primary goal is to safeguard individuals' privacy and guarantee that their personal information is managed responsibly and securely. 

The General Data Protection Regulation (GDPR) is a European Union (EU) law established on May 25, 2018. It regulates the collection, storage, processing, and sharing of personal data. This law applies to any business or organization that handles the personal information of EU citizens, irrespective of its location. 

The Freedom of Information Act (FOIA) gives individuals the right to access information maintained by public authorities. Its purpose is to enhance government transparency and accountability by enabling the public to request and obtain details about governmental actions, decisions, and expenditures. 

The Computer Misuse Act (CMA), introduced in the United Kingdom in 1990, is a law aimed at preventing unauthorized access to computer systems. It protects individuals and organizations from cybercrime, including hacking, fraud, and other digital threats. Similar legislation exists in many other countries to address these issues. 

 Gaining access to a computer system without authorization, such as guessing passwords or using stolen credentials. Example: Hacking into someone’s email account. Penalty: Up to 2 years in prison and/or a fine. Accessing a computer system unlawfully with the intention of committing additional crimes, like fraud or data theft. Example: Hacking into a bank’s system to steal funds. Penalty: Up to 5 years in prison and/or a fine. 

# 🛍️ Retail Sales Data Analysis

## 📁 Dataset Source
The dataset used in this project is "synthetic" and created for educational purposes.  
The dataset includes transaction-level sales data with customer and product details.

## Overview

This project explores retail sales data to uncover business trends, customer behavior, and product performance using **Excel**, **Python (Pandas)**, and **SQL**. The goal is to provide insights that drive decisions in inventory management, marketing strategy, and profitability.

## 🗂️ Dataset

The `retail_sales.csv` dataset contains transaction-level sales data with the following key columns:
- `TransactionID`
- `Date`, 'customer ID', 'Gender', 'Age', 'Generation', 'Product Category', 'Quantity', 'Price per Unit', 'Total Sales;


## Tools Used

  * Microsoft Excel**: Pivot Tables, Data Cleaning, Charts
  * Python (Pandas)**: Data preprocessing, exploration, and advanced analysis
  * SQL**: Aggregations, filtering, grouping, subqueries


## Project Workflow

### 📗 Excel Analysis
- Cleaned raw data: removed nulls, fixed formats
- Created Pivot Tables to summarize:
  - product category by gender
  - Slcing using gender, product category, price unit
- Built charts: Column, Line, and Pie Charts for key performance indicators



























 

![image](https://github.com/user-attachments/assets/7886420a-4175-4f04-884b-fb537d8639f4)
![image](https://github.com/user-attachments/assets/41129133-f10b-48e9-b4fd-349b981e2e99)

product Category



List Unique Product Categories
To extract a list of all unique product categories from column `J` (assumed to be `Product_Category`):

excel
=UNIQUE(J2:J1000)


![image](https://github.com/user-attachments/assets/1171ccd1-87eb-4499-8561-89cbe9091ca1)


total sales =sum(M:M)

total sales for Clothing =sum(j2: j1001, "Clothing", m2: m1001)

total sales for Beauty =sum(j2: j1001, "Beauty", m2: m1001)

totaal sales for Electronics =sum(j2: j1001, "electronics", m2: m1001) 





![image](https://github.com/user-attachments/assets/754fc980-a279-4f6f-a701-dbec673d4bbd)




This total sales can be used to compare last year's sales and it can be used to predict next year sales.






 


total sales for male in Clothing category =sumifs(k2: k1001, j2: j1001, "Clothing", G2: G1001, "Male")

total sales for male in Beauty category =sumifs(k2: k1001, j2: j1001, "Beauty", G2: G1001, "Male")
 
totaal sales for male in Electronics category =sumifs(k2: k1001, j2: j1001, "Electronics", G2: G1001, "Male")
   








 

![image](https://github.com/user-attachments/assets/e9b0f6ef-66c7-4655-8812-815165dda8aa)

![image](https://github.com/user-attachments/assets/bce91933-707b-4a8a-8984-22e0124161ab)

 Here I used pivot table and slicing to filter and sort the data


![image](https://github.com/user-attachments/assets/fb306f15-db84-4cf7-ab2c-75cad223dabe)



 

 























