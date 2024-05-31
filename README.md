# DiCo Fashion Sales Analysis

Welcome to the DiCo Fashion Sales Analysis project repository. This project aims to evaluate the sales performance and customer behavior for Dicoding Collection (DiCo), an online fashion retailer. Through this analysis, we seek to identify top-selling products, understand customer demographics, and provide actionable insights for more effective marketing campaigns.

## Introduction

Dicoding Collection (DiCo) is an online fashion retailer that manufactures and sells various fashion items through its online platform. Understanding the importance of data for business growth, DiCo has maintained a structured database containing sales history, product details, and customer information.

## Dataset Overview

The dataset used in this project is provided by Dicoding and includes information on online fashion sales, structured into four tables:

- **Customers:** Contains details such as customer_id, customer_name, gender, age, home_address, zip_code, city, state, and country.
- **Orders:** Includes order_id, customer_id, order_date, and delivery_date.
- **Products:** Provides information such as product_id, product_type, product_name, size, colour, price, quantity, and description.
- **Sales:** Details each transaction with sales_id, order_id, product_id, price_per_unit, quantity, and total_price.

You can find the dataset [here](https://github.com/dicodingacademy/dicoding_dataset/tree/main/DicodingCollection).

## Goal

Evaluating sales performance and customer behavior to identify top-selling products, understand customer demographics, and provide insights for more effective marketing campaigns based on the analysis.

## Executive Summary

The analysis revealed key insights into the company's performance and customer behavior:
- **Sales Performance:** Sales and revenue peaked in March and were lowest in October.
- **Product Analysis:** Denim was the most popular product, while Mandarin Collar had the fewest sales.
- **Customer Demographics:** A large portion of customers did not disclose their gender. The majority of customers were adults, primarily from South Australia.
- **Customer Transaction Analysis:** The average time since the last transaction was 122 days, with an average purchase frequency of 1.61 times and a maximum of 6 times. Top spenders had monetary values exceeding 7,000.
- **RFM Analysis:** Identified the most recent, frequent, and high-spending customers.

## Analysis and Findings

The analysis covers:
1. **Sales Performance and Revenue Trends**
2. **Product Popularity Analysis**
3. **Customer Demographics Breakdown**
4. **Customer Purchase Patterns**
5. **RFM (Recency, Frequency, Monetary) Analysis**

## Tools Used

- **Python:** For data cleaning, analysis, and visualization (Pandas, Matplotlib, Seaborn).
- **Google Colab:** For collaborative coding and running Jupyter Notebooks.

## Conclusion

This comprehensive analysis helps DiCo to better understand their sales performance, product popularity, and customer behavior, enabling more targeted and efficient marketing strategies. The findings from the RFM analysis provide actionable insights into customer segmentation, which can be leveraged to enhance customer retention and boost sales.
