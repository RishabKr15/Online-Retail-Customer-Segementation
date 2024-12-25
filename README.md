# Online-Retail-Customer-Segementation
![target-group-large](https://github.com/user-attachments/assets/df6ee5e2-f194-4cf8-ba2d-54d2f84b2dbd)



# Indroduction:-
Businesses all over the world are growing every day. With the help of technology, they have access to a wider market and hence, a large customer base. Customer segmentation refers to categorizing customers into different groups with similar characteristics.

This project aims to identify major customer segments on a transnational data set for a UK-based online retail.

# Problem Description :
In this project, my task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. rfm_model

# The need of customer segmentation:
The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:

Target Marketing

Client understanding

Optimal product placement

Revenue growth

# Recency-Frequency-Monetary (RFM) model to determine customer value:
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?

Frequency – How often do they purchase?

Monetary Value – How much do they spend?

A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

# ALGORITHM
## K-Means Clustering Algorithm

K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabelled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.
It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabelled dataset on its own without the need for any training.It is a centroid-based algorithm, where each cluster is associated with a centroid. The main aim of this algorithm is to minimize the sum of distances between the data point and their corresponding clusters.The algorithm takes the unlabelled dataset as input, divides the dataset into k-number of clusters, and repeats the process until it does not find the best clusters. The value of k should be predetermined in this algorithm.
The k-means clustering algorithm mainly performs two tasks:
 Determines the best value for K centre points or centroids by an iterative process.
 Assigns each data point to its closest k-centre. Those data points which are near to the particular k-center, create a cluster.Hence each cluster has data points with some commonalities, and it is away from other clusters.
The below diagram explains the working of the K-means Clustering Algorithm:
![image](https://github.com/user-attachments/assets/1c03ced2-9c4a-4739-85ee-9a4923ba22ec)

## Elbow Method 
It is an empirical method to find the optimal number of clusters for a dataset. In this method, we pick a range of candidate values of k, then apply K-Means clustering using each of the values of k. Find the average distance of each point in a cluster to its centroid, and represent it in a plot. Pick the value of k, where the average distance falls suddenly.
![image](https://github.com/user-attachments/assets/aa583acb-3550-418a-8536-aee1c36b9a1e)



# Approach taken
Data inspection

EDA

Data preparation

Create RFM model

Implementing various clustering Models and validating

# Conclusions:
Customer segmentation is highly effective strategy for organizations because it allows them to know which customers care about them and understand their needs enough to send a message that ensures brand success.
We used RFM Modeling to see the relation between Recency,Frequncy and Monetary.After RFM model we used this data to perform clustering with the help of k mean clustering Algorithm.

Descriptive Analysis: The data exploration of Online customer segmentation dataset shows :

Missing and duplicate values were found.

Most of the purchases are from the United Kingdom.

Most of the customers have purchased items on Thursday, Wednesday, Tuesday.

Most of the customers have purchased items in November, October, December, and the least number of purchases in April, January, February.

Most of the customers purchase in the afternoon time.

Using a recency, frequency and monetary(RFM) analysis, the customers have been segmented into various clusters.

By applying different clustering algorithm to our dataset, we get the optimal number of cluster is equal to 3.

The business can focus on these different clusters and provide customer with services of each sector in a different way, which would not only benefit the customers but also the business at large.

