## Customer Segmentation for Targeted Marketing in E-Commerce

### Module:
WQD7007 Big Data Management 

### Group Members:
| Name | Matric ID|
| ---------------------- |:--------:|
| Low Boon Kiat | 17138399 |
| Zhou Yao | S2177633 |
| Wen Yukun | 22108184 |
| Du Pengfei | S2130205 |
| Ong Yi Kwong | S2181260 |
| Koh Rong Soon | 22061463 |
| Chunli Wang | 22064827 |
| Meng Guan | S2179731 |

### Problem Statement:
Shopee, as an emerging player in the competitive e-commerce market, faces the challenge of effectively understanding its diverse user base to optimize marketing efforts, enhance user experience, and drive platform growth. Based on Measurable AI’s data in 2023 Q1, Southeast Asian consumers have showcased steadfast loyalty to Shopee over the years with an average customer retention rate of ~49% (Sheng, 2023). There remains untapped potential for improvement. The challenge lies in accurately segmenting a diverse customer base into distinct groups based on their purchasing patterns, demographics, and interactions with the platform to allow for targeted marketing. To address the problem statement, we examine the following questions to provide crucial insights that can inform customer segmentation strategies.    

_Segmentation by geographical location_ 
- Which cities are generating the highest orders?  
- Which cities are generating the most revenue?   

_Time-based segmentation_  
- What are the peak order timings?  
- What are the peak order days?   

_Product preference segmentation_  
- What are the best and the worst performing product categories in terms of number of orders?  
- What are the best and the worst performing product categories in terms of total revenue generated?  
- What are the best and the worst performing product categories in terms of review scores?   

_Payment behaviour segmentation_  
- What are the most popular payment methods?  

_Service-related segmentation_  
- How long does it take for the products to be delivered?  
- Do longer delivery times lead to poor review scores?  

### Dataset:
- Brazilian E-Commerce Public Dataset by Olist on [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Provide information of 100,000 orders made across multiple marketplaces in Brazil from 2016 to 2018.
- Encompass various dimensions such as order status, pricing details, payment and freight performance, customer location, product attributes and customer reviews.

### Methodology:
_Data Pre-processing:_  
- Join six raw datasets into one using common columns that serve as primary keys.  
- Remove comma and "Enter" in "review_comment_message" column to avoid affecting the CSV format.  
    
_Data Storage:_  
- Load data into storage using MySQL and HBase.  
- Retrieve information about the MySQL and HBase table e.g. table structure, data type of each column.  
    
_Data Access:_  
- Perform 13 queries using Hive and Pig to provide insights for customer segmentation.  
    
_Performance Evaluation:_  
- Compare the read/write performance of each tool (MySQL vs. HBase, Hive vs. Pig).  
