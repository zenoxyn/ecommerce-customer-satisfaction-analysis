# 📦 E-Commerce Customer Satisfaction Analysis

## 📌 Project Overview
This project analyzes customer satisfaction using a real-world Brazilian e-commerce dataset (Olist).  
The goal is to uncover key factors influencing customer reviews, especially focusing on shipping delays and product categories.

## 🎯 Objective
- Investigate the impact of delivery time on customer review scores
- Identify top product categories with the highest average ratings
- Provide actionable business recommendations to improve satisfaction

## 📂 Dataset
Source: [Olist E-Commerce Public Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Used Files:
- `olist_orders_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`

## 🔍 Analysis Process
- Merged multiple datasets using `order_id` and `product_id`
- Calculated delivery duration from purchase to delivery date
- Visualized the relationship between delivery time and review score
- Aggregated average review scores by product category

## 📊 Insights & Findings
- Longer delivery times tend to result in lower customer review scores (1–2 stars).
- Most customers gave a review score of 5, but late deliveries are a strong reason for negative reviews.
- Product categories such as *toys*, *books*, and *baby products* consistently received high ratings.

## ✅ Conclusions & Recommendations
- Faster shipping significantly increases customer satisfaction.
- E-commerce platforms should focus on improving logistics and delivery efficiency.
- Product categories with poor ratings (e.g., electronics) should receive more quality control attention.

## 🤖 AI Support (Granite Model via LM Studio)
This project also utilized **Granite AI Model via LM Studio** to support:
- Summarizing analytical insights
- Rewriting recommendations in a more professional business tone

### 🧠 Prompt used in LM Studio:
I analyzed an e-commerce dataset and found that customers often leave low ratings when deliveries are late. Categories such as toys and books tend to receive higher ratings. Please generate a business insight summary and recommendation based on these findings.


### 📝 AI-Generated Output:
Summary of Insights:
1. Shipping Experience:
Customer reviews show that long delivery times generally have a negative impact on product ratings. Delays in shipping can lead to negative reviews, affect customer loyalty, and potentially harm the business by losing future purchase opportunities.
2. Product Categories:
Based on data analysis, product categories such as books and toys tend to receive higher ratings. This may be related to factors like customers’ need for quality, expectations around delivery timing, and distinct shopping experiences compared to other product types.

Business Recommendations:
1. Address Shipping Challenges:
Improving the shipping system can boost customer satisfaction and reduce negative reviews caused by long delays. This can be achieved through better stock management, routine order fulfillment optimization, and selecting faster, more effective delivery services.
2. Understand Other Product Categories:
Identifying what makes books and toys more attractive to customers compared to other products can help inform marketing strategies for other categories. For instance:
- If customers value high quality and calm shopping experiences, this should be analyzed and applied across all product types.
- If there's a difference in delivery expectations between digital products (like books) and physical items (like toys), order fulfillment strategies can be tailored accordingly.
3. Monitor and Manage Online Reputation:
Consistently monitoring and analyzing customer reviews is crucial to tracking satisfaction trends. Regularly reviewing feedback, understanding its content, and taking steps to resolve identified issues (such as fixing delivery processes) are essential.
4. Customer Satisfaction Program:
Building a Customer Satisfaction Loyalty (CSL) program can improve business success by offering exclusive product or service benefits to loyal customers. This can encourage repeat purchases, drive referrals, and reduce the risk of losing customers to competitors.
5. Strategic Marketing:
To boost the popularity of other products, businesses can focus their marketing efforts on customer needs like product quality and shopping experience. Creating digital content, engaging with online communities, and maintaining active social media management can help increase purchases across different categories.


## 🧰 Tools Used
- **Google Colab** (Python, Pandas, Seaborn, Matplotlib)
- **LM Studio** (Granite Model)
- GitHub for version control


## 📎 Author
Novanda Ega Arenta


