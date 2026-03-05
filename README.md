# Online Store Sales Analysis


## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights) and Recommendations
- Conclusion

## 📊 Project Overview

Analyzing different sales trend based on the given dataset using dashboard.

The dataset contains 1201 rows and 14 columns containing details of orders, products, customers and sales data.


## 🗂️ Data Source

**Source:** Web scraping 

**size:** 357 KB

**key variables:** Order ID, Date, Customer ID, Product, Quantity, Unitprice, Shipping Address, Payment Method, Order Status, Tracking Number, Items in Cart, Coupon code, Referral Source, Total Price.


## 🛠️ Tools & Technologies


- **Visualization:** MS Excel
  
- **Documentation:** MS Word

  
## 🧹 Data Cleaning & Preparation

•	Converted given dataset into table format

•	Changed datatypes for every single column

•	Sorted date column in ascending order

•	Created new column named “Month” using formula

         =TEXT(B2,”mmm”) 
         
•	Found missing values in coupon code column and replaced with “Null” using formula

    =IF(ISBLANK(M2),”Null”,M2) 
    
•	Added a new sheet and named Descriptive statistics and copied product column, Quantity column, Unit Price column and Total price column from the given dataset.

•	Calculated Mean, Median, Mode, Sum, Count and all other calculations using Analysis Toolpak.


## 🔍 Exploratory Data Analysis (EDA) 

•	Comparing Products and Total sales Chair and Printer ranked High in sales whereas Phone ranked Least in sales.

•	Comparing Products and Quantity sold Chairs sold in Higher quantity whereas Phone sold in Least quantity.

•	Comparing Months and total orders June month got more orders than every other month whereas September month got least orders.
  There is a decrease in sales pattern.

•	Comparing order years and total sales and Quantity 2023 shows more sales and 2025 shows least sales.
  
•	Though 2025 has only 6 months.

•	But still, there is a fall in sales pattern.

•	It is necessary to change sales strategies to improve pattern.



<img width="1019" height="525" alt="image" src="https://github.com/user-attachments/assets/c3313ae4-fdf2-4448-bb9b-9047e2b8c800" /> 



## 💡 Key Insights and Recommendations:

•	The Online store sales were analyzed and insights gathered.

•	Phones sold in less quantity compared to other products and chairs and printer sold in higher quantity.

•	Strategies shall be applied to increase phone sales.

•	Overall sales pattern seems to be decreasing from 2023 to 2025. Discounts and Advertisements may help increase in sales.



## Conclusion:

• The integration of Excel proved effective for end-to-end data analysis, from raw data to visual reporting.
