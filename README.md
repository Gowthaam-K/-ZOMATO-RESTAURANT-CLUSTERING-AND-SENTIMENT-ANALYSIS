# ZOMATO-RESTAURANT-CLUSTERING-AND-SENTIMENT-ANALYSIS
We are provided with two datasets; one is the metadata dataset and the other one is the Reviews dataset. 
The Project focuses on Customers and companies, we have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the Zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data in an instant. The Analysis also solve some of the business cases that can directly help the customers find the best restaurant in their locality and for the company to grow up and work in the fields they are currently lagging in.

At first, we performed Data cleaning by creating a data frame and removing unnecessary columns with null values, dropping the duplicate rows in this dataset, and started getting basic insight from the cleaned dataset.

We have performed some text preprocessing on some columns to make them efficient for us to implement our clustering models, and also performed visualization to get basic insights on the features. 

We went with feature conversion in which the object datatype features are converted to numeric features in our dataset.

After feature selection, we tend to split the data into clusters and started implementing basic Machine Learning Models for clustering

The Models Were:
a) K – means clustering
b) Hierarchical clustering
c) Agglomerative clustering 
d) DBSCAN clustering 
After merging two datasets we tend to perform sentiment analysis on the clusters that we have separated using VADER MODEL and TEXT BLOB MODEL.
The main objective of sales forecasting is to paint an accurate picture of expected sales by targeting the clusters. Sales teams aim to either hit their expected target or exceed it. When the sales forecast is accurate, operations go smoothly and future planning for the company's growth is done efficiently.
