# Mall Customer Segmentation
## Overview
This project focuses on segmenting customers of a mall using unsupervised machine learning techniques. Customer segmentation helps businesses understand their clients better and tailor marketing strategies, leading to improved customer satisfaction and increased sales.

## Dataset
The dataset used is from public dataset published at Kaggle (https://www.kaggle.com/datasets/zubairmustafa/shopping-mall-customer-segmentation-data). It contains information about mall customers, including demographic and transactional data.:

- Customer ID: A unique identifier for each customer
- Age: The age of the customer
- Gender: The gender of the customer
- Annual Income ($): Annual income of the customer
- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending habits

## Methodology
1. **Data Preprocessing**: Clean and prepare the dataset, checking missing values
2. **Feature Engineering**: Encoding categorical features using label encoding, choosing important features, and scaling numerical features to improve model performance
3. **Number of Clusters**: Choosing the number of clusters using Elbow Method and Calinski-Harabasz Index
4. **Clustering**: Apply K-Means clustering algorithms to segment customers
5. **Clusters Identified**: The clustering algorithm identified 4 distinct segments, which can be summarized as follows:
   - Cluster 0: Middle-aged customer, lower income, lower spending score
   - Cluster 1: Younger customer, higher income, medium spending score
   - Cluster 2: Older customer, higher income, medium spending score
   - Cluster 3: Middle-aged customer, lower income, higher spending score
![image](https://github.com/user-attachments/assets/55c6e92c-2d57-4af7-abd6-d35e2e738af3)

## Recommendation
- Cluster 0: Stock and promote more affordable products that align with their needs, such as budget-friendly brands or value packs. Implement a loyalty program that rewards frequent visits or purchases.
- Cluster 1: Introduce a range of trendy and premium products that appeal to younger consumers' preferences and lifestyles. Utilize social media platforms for targeted advertising and engagement.
- Cluster 2: Offer exclusive products or services, like premium memberships or access to private sales, to enhance their sense of value and exclusivity. Focus on health and wellness items, such as organic foods or fitness-related products.
- Cluster 3: Provide value-oriented offers or bundle deals that allow them to maximize their spending. Engage with this segment to understand their shopping motivations and preferences.

## Conclusion
The analysis of customer segmentation usign K-Means Clustering successfully identified customer segments that can help the mall tailor its marketing strategies and enhance customer engagement. Further analysis could be conducted to refine these segments or to explore additional features.
