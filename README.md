# Warehouse Location Estimator

## Demonstration of weighted K-Means Algorithim

#### OBJECTIVE
Determine the location of new warehouse to be set up across the Java Island of Indonesia for a newly set up fast food chain.While determing these location we should take into account the population of each cities that needs to be served.

This is a demonstration of the solution to the above problem.Warehouse location is determied by using KMeans clustering where the centroid of each clusters is the proposed location. Number of warehouse required is pre specified.  

Weighted KMeans algorithim is implemented where the centroid of each clusters is calculated as a weighted mean of all the datapoints in that cluster along with the population of those cities as its weights.  

Based on https://towardsdatascience.com/using-weighted-k-means-clustering-to-determine-distribution-centres-locations-2567646fc31d
