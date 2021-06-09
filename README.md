# Data-Mining

A leading bank wants to develop a customer segmentation to give promotional offers to its customers. They collected a sample that summarizes the activities of users during the past few months. You are given the task to identify the segments based on credit card usage.

## Data Pre-processing:

Data Pre-processing involves steps like data cleaning, data integration, data transformation, data reduction and data discretization

•	There are total 210 rows and 7 columns in the dataset.
•	There are 0 null values present in the dataset.
•	Number of duplicate rows = 0
•	Converting the values of dataset by its multiples.

 ## Inference:
The variables of the data set are of different scales i.e. one variable is in thousands and other in decimals. For e.g. in our data set “credit limit” is having values in thousands and “probability of full payment” is in decimals. Since the data in these variables are of different scales, it is tough to compare these variables.

## Do you think scaling is necessary for clustering in this case? Justify
•	Data Mining can generate effective results if normalization is applied to the dataset. It is a process used to standardize all the attributes of the dataset and give them equal weight so that redundant or noisy objects can be eliminated and there is valid and reliable data which enhances the accuracy of the result. K-Means algorithm uses Euclidean distance that is highly prone to irregularities in the size of various features. 
•	There are various data normalization methods like Min-Max, Z-Score etc.. The best normalization method depends on the data to be normalized. Here, we have used Min-Max normalization technique in our algorithm because our dataset is limited and has not much variability between minimum and maximum. 
•	Min-Max normalization technique performs a linear transformation on the data. In this method, we fit the data in a predefined boundary or in a predefined interval.

## Describe cluster profiles for the clusters defined. Recommend different promotional strategies for different clusters.

## Hierarchical clustering:
Cluster Frequency:
•	Cluster 1    67
•	Cluster 2    53
•	Cluster 3    90

 ## Inference:
•	Cluster 1: Customers that are big spender and pays large amount advances.
•	Cluster 2: Customers that are High spenders with lowest minimum payment and has low credit limit.
•	Cluster 3: Customers that are smallest spenders with highest minimum payment and lowest credit limit.
 	Recommendations:

•	The goal was to segment the customers of a bank to give promotional offers.
•	Cluster 1: These customers are big spender and gives large payments in advance. Customers with high average card spend and high average balance are typically those customers who are economically stable and have high spending capacity. So, can promote various expensive brand-new credit card product to these customers to increase their credit limit and so that they spend more. They are 67 customers.

•	Cluster 2: These customers are high average spenders and has low credit limit i.e. low average balance. Economically they may not be stable but have high potential of purchasing/spending because of various reasons. So, can offer a loan to increase their spending. Offering loan to these customers will not make much difference as they have high balance anyway. They are 53 customers.

•	Cluster 3: These customers are Smallest Spenders and has lowest credit limit., but minimum paid by the customer while making payments for purchases made monthly are highest than customers in cluster 1 & 2. So, can promote various monthly shopping schemes as well as loans to these customers to increase their monthly shopping. They are 90 customers.

##	Conclusion:

•	In this project, we went through the customer segmentation model. We developed this using a class of machine learning known as unsupervised learning. Specifically, we made use of a clustering algorithm called K-means clustering. We analysed and visualized the data and then proceeded to implement our algorithm. With the help of clustering, we can understand the variables much better, prompting us to take careful decisions. With the identification of customers, bank can release different promotional schemes that target customers based on several parameters like credit limit, payments, spending patterns, etc. Furthermore, more complex patterns like income, shopping patterns are taken into consideration for better segmentation.
•	The K-means clustering algorithm is widely used for clustering huge data sets. But traditional k means algorithm does not always generate good quality results as automatic initialization of centroids affects final clusters. This analysis presents an efficient algorithm where we have first pre-processed our dataset based on normalization technique and then generated effective clusters. This is done by assigning weights to each attribute value to achieve standardization. Our algorithm has proved to be better than traditional K-means algorithm in terms of execution time and speed.


