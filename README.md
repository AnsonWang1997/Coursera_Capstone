# Coursera_Capstone
This Capstone project aims to utilize location data to analyze neighborhoods in New York City, Toronto and Paris.

## 1. Introduction:
In this project, we utilized location data to analyze, cluster and compare neighborhoods in New York, Toronto and Paris to detect the differences and similarities of the distribution of business over these cities. 

We identified the most dense and welcome neighborhood business that these cities share in common. Business landers may refer to this study to obtain basic ideas about which kind of business is more likely to thrive and start with and which is not very desirable in these world-famous cities. Stakeholders with stocks relevant to these cities can better understand certain local economic drives there and improve their decision models. 

It's well recognized that these cities are most popular over the seas. With an estimated 2020 population of 8,336,817 distributed over about 784 square kilometers, New York City is also the most densely populated major city in the United States. Meanwhile, Toronto, the capital of Canada, is often described as "New York City run by the Swiss" with world-class theater, shopping and restaurants. Paris is the capital and most populous city of France, with an estimated population of 2,148,271 residents as of 2020, in an area of 105 square kilometers, and has been one of Europe's major centers of finance, diplomacy, commerce, fashion, science and arts. A large amount of capitals and opportunities are flowing through these dynamic cities. Therefore, it's worth it to explore and analyze the patterns of the business distribution to deliver insights for commercial kickoff, extension and development.

## 2. Data:
The data to be used in this project is basically the neighborhood data, and venue information obtained from Foursquare. We're supposed to gather the neighborhoods in each city and then check the venues inside each neighborhood and which category they belong to. 

The features in the neighborhood dataframe should contain the name of neighborhoods, the location (longitude, latitude) and hopefully the postal code. 

The features in the venue information dataframe should include the name of the venue, the neighborhoods it currently belongs to, and the venue's type of business. The dataframe will be merged and aggregated with one-hot encoding to find the business distribution of these cities, which is the fundamentals of the following clustering operations

## 3. Methodology:

Clustering is one of the most common exploratory data analysis technique used to get an intuition about the structure of the data. It can be defined as the task of identifying subgroups in the data such that data points in the same subgroup (cluster) are very similar while data points in different clusters are very different.

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid.

Another way, which is more advanced in data mining, is the hierarchical clustering. Hierarchical clustering is separating data into groups based on some measure of similarity, finding a way to measure how they’re alike and different, and further narrowing down the data.

## 4. Files:
Please refer to the report.pdf and the notebook Battle of Neighborhoods for the final project. Additionally, the Toronto location data analysis notebook in week 2 and week 3 are practice assignments of the coursera course. If you met any other issues with the document, please reach out to me.
