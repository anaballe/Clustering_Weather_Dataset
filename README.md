# Cluster Analysis on a Weather Dataset using K-Means Clustering Algorithm Using Spark Execution Engine over a Databricks Cluster

 I have performed cluster analysis on the ​minute-weather.csv ​ dataset using
the k-means algorithm. This dataset contains weather measurements such as
temperature, relative humidity, etc., from a weather station in San Diego, California, collected at
one-minute intervals. The goal of cluster analysis on this data is to identify different weather patterns
for this weather station.

I have performed the following :-
1. Scale all features so that each feature is zero-normalized
2. Create an "elbow" plot, the number of clusters vs. within-cluster sum-of-squared errors, to
determine a value for k, the number of clusters in k-means
3. Perform cluster analysis on a dataset using k-means
4. Create parallel coordinates plots to analyze cluster centers

The dataset(minute_weather.csv) can be downloaded from the link https://drive.google.com/file/d/1HrOMag0s4FNzW9RcVWO3iHCGhUufnJvd/view?usp=sharing 
