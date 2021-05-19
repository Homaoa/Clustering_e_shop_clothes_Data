# Clustering_e_shop_clothes_Data


A clustering model is developed for clickstream data for online shopping Data Set. The raw data is obtained from UCI website. Data cleaning and preparing and model building are done on the data. K-means model and Hierarchical model are considered.


Data source : https://archive.ics.uci.edu/ml/datasets/clickstream+data+for+online+shopping#


Data cleaning :

The raw data from UCI was not prepared. I have cleaned the data, defined needed variables, and I have corrected the type of variables too.

EDA :

I have used histograms and bar charts to gain some insight from the data. Some variables types had to be defined which I did based on the variables values.

Model :

After EDA part, I have started the machine learning phase of the project. K-means and Hierarchical models have been used in order ot cluster the data. The optimized number of clusters have been found by using elbow method. A new variable is defined that shows the cluster of each observation. This variable then can be added to the data frame as a new column.
