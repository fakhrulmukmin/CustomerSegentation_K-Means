# Customer Segentation K-Means For Retail Industry
Data Source : https://www.kaggle.com/datasets/carrie1/ecommerce-data

Acknowledgements: Per the UCI Machine Learning Repository, this data was made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.


Over the years, the retail industry is becoming more competitive, as such organizations have to satisfy the needs and wants of their customers, attract new customers, and hence enhance their businesses. Customers may have differences in their needs, want, demography, geography, tastes and preferences, behaviors, etc. This challenge has motivated the idea of customer segmentation, customer segmentation itself is a strategy of dividing the market into homogeneous groups. Developing several clustering models to gain a better understanding to gain understand about customer segmentation and identify business strategies for each types of customer.

The Clustering model I will use are: 
1. K-means Clusters: Elbow Method
2. K-means Clusters: Silhouette Method


k-Means algorithm is one of most popular partitional clustering algorithm. It is a centroid-based algorithm in which each data point is placed in exactly one of the K non- overlapping clusters selected before the algorithm is run.

Generic k-means clustering Algorithms: 
1. Decide on the number of clusters, k. 
2. Initialize the k cluster centroids 
3. Assign the n data points to the nearest clusters. 
4. Update the centroid of each cluster using the data points therein. 
5. Repeat steps 3 and 4 until the changes in positions of centroids are zero. 

There is 3 clustering
- Group 1 : customer spent up to $2500 per purchase and their lastest order is within 3 months
- Group 2 : customer spent up to $1500 per purchase and their lastest order is between 3 months to 13 months
- Group 3 :customer spent from $ 1500 to 3500 per purchase and their lastest order varies from 1.5 month to 13 months

Business recommendation
- Group 1 : Loyalty programs, Maintain a positive attitude, Respond quickly, Be proactively helpful
- Group 2 : Be proactively helpful, Focus support on the customer, Bundling Product, Engage customers on social media, Encourage customer feedback.
- Group 3 : Getting something free, Reward your customers, Ask for advice and listen to it, Offer conveniences, Provide Extra Value, Promote your brand in a variety of ways.


 










