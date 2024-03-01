# Capstone_Unsupervised - Online Retail Customer Segmentation

# Introduction

We are provided with a transnational dataset. The objective of this project is to segment customers.

# Problem Statement

The objective of this project is to segment customers based on a transnational dataset that includes all transactions between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company specializes in selling unique all-occasion gifts, with a significant portion of its customer base consisting of wholesalers. The goal is to identify distinct customer segments within the dataset to better understand customer behavior and tailor marketing strategies accordingly.

# Dataset Information

The variables are described as follows:

**InvoiceNo :** 6-digit integral number uniquely assigned to each transaction where starting letter 'c' indicates a cancellation. (Nominal)

**StockCode :** 5-digit integral number uniquely assigned to each distinct product.(Nominal)

**Description :** Item name(Nominal)

**Quantity :** Quantities of each item per transaction (Numeric)

**InvoiceDate :** The day and time when each transaction was generated (Numeric)

**UnitPrice :** Product price per unit in sterling (Numeric)

**CustomerID :** a 5-digit integral number uniquely assigned to each customer(Nominal)

**Country :** Name of the country where each customer resides(Nominal)

# Data Cleaning and Manipulation

1. Handling Null & Duplicate Values

2. Converting Datatypes

3. Creating New Columns

# EDA

The data visualization is performed using mainly seaborn & matplotlib library. For visualization, the following charts are used:

Bar plot

Count plot

Distplot

Scatter plot

Correlation Heatmap

Pair plot

# ML Model 

1. K-Means Clustering with Silhouette Method
   
K-Means clustering is a popular unsupervised machine learning algorithm used for partitioning data into K distinct clusters. The Silhouette method is a technique used to evaluate the quality of clustering by measuring how well-separated the clusters are.

2. K-Means Clustering with Elbow Method
   
The K-Means clustering algorithm is widely used for partitioning a dataset into a predetermined number of clusters. The Elbow method is a technique used to find the optimal number of clusters by plotting the within-cluster sum of squared distances (WCSS) against the number of clusters.

3. Agglomerative Clustering
   
Agglomerative clustering is a hierarchical clustering technique used to group similar data points into clusters. It starts with each data point as a separate cluster and then merges the closest clusters iteratively until only one cluster remains.

# Conclusion

The objective of this project is to segment customers based on a transnational dataset that includes all transactions between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. To ensure the integrity of the original dataset, we created a duplicate copy for subsequent manipulations, safeguarding the primary data from unintended alterations. We eliminated both null values and duplicates from the dataset.

The United Kingdom emerges as the leading region in terms of transaction count, indicating a strong customer base or market presence in that region. Thursday stands out as the day with the highest transaction count, suggesting heightened activity or sales on that particular day of the week. Moreover, November emerges as the month with the highest transaction count, possibly indicating increased sales activity due to seasonal factors or promotions during that period. Additionally, transactions peak at 12 pm, suggesting a surge in sales activity during the midday hours. Furthermore, the afternoon emerges as the time period with the highest product sales, underscoring the significance of afternoon hours in driving sales volume.

In our analysis, we explored three distinct clustering techniques to identify meaningful patterns within the dataset: K-means clustering with the silhouette method, K-means clustering with the elbow method, and agglomerative clustering. Through the application of various clustering algorithms to our dataset, we identified that the optimal number of clusters is 2. This finding underscores the importance of segmentation in understanding customer behavior and preferences. With this knowledge, businesses can effectively allocate resources, tailor marketing initiatives, and optimize operational strategies to maximize customer engagement and retention. The insights gained from RFM analysis and clustering enable businesses to make informed decisions that lead to improved customer experiences and sustainable business success.

Each method offers unique insights into the underlying structure of the data and helps us uncover clusters or groups that share similar characteristics. By comparing the results obtained from these different approaches, we can gain a comprehensive understanding of the data and extract valuable insights that can inform decision-making processes.
