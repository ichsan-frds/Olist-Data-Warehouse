# Olist Data Warehouse

# Business Understanding
![image](https://github.com/user-attachments/assets/48f6628f-5ae8-4ec9-a0cc-18240bea18a6)

## About Olist Store
Olist is a Brazilian B2B e-commerce company that helps small and medium-sized businesses sell their products on major online marketplaces. By aggregating merchants into its platform and handling logistics and operations, Olist enables them to reach a wider customer base without needing to manage multiple sales channels individually.

## Business Model Overview
Olist acts as a marketplace integrator that connects small and medium-sized sellers across Brazil to major e-commerce platforms. Sellers list their products on Olist, which then distributes them across various marketplaces where customers place their orders. The order fulfillment is handled directly by the sellers, while Olist supports logistics and communication. After delivery, customers can provide ratings and reviews. This model creates a complex ecosystem involving multiple sellers, diverse product categories, varied delivery paths, and several customer satisfaction factors.

## Business Goals
To improve platform performance, customer satisfaction, and seller efficiency, Olist has four main goals. First, enhance customer experience by reducing late deliveries and identifying the causes of negative reviews. Second, increase operational efficiency by optimizing logistics, minimizing returns and cancellations, and monitoring seller performance. Third, maximize marketing conversion by understanding which channels drive purchases and linking them to successful orders. Lastly, drive revenue and retention by promoting high-value products and retaining high-lifetime-value customers.

# Dataset
[[Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)]

# Problem
One of the major challenges in e-commerce is the vast amount of data that is often scattered and unstructured. With transactions, customer interactions, logistics, reviews, and marketing data coming from various sources, managing and organizing this information becomes complex. Moreover, regular analysis is crucial across all departments—such as sales, customer service, logistics, and marketing—to support informed decision-making. Without a well-structured and centralized data warehouse, it becomes difficult to perform reliable, efficient, and timely analysis, which can hinder business growth and responsiveness.

# Dimensional Model
![image](https://github.com/user-attachments/assets/ab24574d-2c94-4e94-ad46-d5689c44a79a)

# Architecture Diagram
![image](https://github.com/user-attachments/assets/043fa310-607f-41f1-9053-a79da6f166cd)

# ETL
![image](https://github.com/user-attachments/assets/740dd8f4-4607-401f-8a5f-616f5066d224)

# Final Schema
![image](https://github.com/user-attachments/assets/fcebc8d1-7d86-454d-ba30-b0dded6252e2)

# Dashboard
![image](https://github.com/user-attachments/assets/9623c4e7-914e-40e3-9a8c-8ebab4ba3e40)
1. Total (Distinct Count) of All Orders from 2016 - 2020 & Values (Sum) of both Successful and Rejected Orders
2. Date Slicer (affects all other visualization)
3. Total (Distinct Count) Orders by Product Category Order by Highest Total Orders
4. Customer State Distribution (Customer Distinct Count by their Geolocation State)

