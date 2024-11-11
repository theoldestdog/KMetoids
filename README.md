# KMetoids
Data clustering using sklearn KMetoids

This is a project to cluster retail data using KMetoids and comparing the results to the output from KMeans clustering.
The data set is common to both and is aggregated on Customer ID, log transformed and MinMax scaled.

The data has many significant outliers in MonetaryValue and Frequency. IRL these would be very important and would be segmented out
and examined on their own.

This process is meant to see if there is a meaningful difference between KMeans and KMetoids clustering given KMetoids is said to handle
outliers more effectively than KMeans due to the methodology differences.
