## Machine Learning Assignment: Dividing people on Wikipedia into k categories by their profiles

The first task is to use k-means++ method to separate 59071 people's Wikipedia pages into k categories. Machine Learning library is not used.

Here is the output of k = 10 categories, each visualised by the top 5 words that have the highest tf-idf weights in the centroid of that category.
```
Cluster 0     film:0.020 art:0.014 he:0.011 book:0.010 television:0.010 

Cluster 1     league:0.052 rugby:0.044 club:0.042 cup:0.042 season:0.041 

Cluster 2     championships:0.040 tour:0.037 championship:0.032 world:0.029 won:0.029

Cluster 3     baseball:0.110 league:0.103 major:0.052 games:0.047 season:0.045 

Cluster 4     research:0.038 university:0.035 professor:0.032 science:0.023 institute:0.019

Cluster 5     football:0.076 coach:0.060 basketball:0.056 season:0.044 played:0.037 

Cluster 6     she:0.138 her:0.089 actress:0.014 film:0.013 miss:0.012 

Cluster 7     music:0.057 album:0.040 band:0.035 orchestra:0.023 released:0.022 

Cluster 8     hockey:0.216 nhl:0.134 ice:0.065 season:0.053 league:0.047

Cluster 9     party:0.028 election:0.025 minister:0.025 served:0.021 law:0.019
```


In the second task, k-means algorithm is used to generate proper initial means for Expectation Maximization (EM) algorithm. 
To reduce complexity, the covariance matrix of components is assumed to be a diagonal matrix.

Below is the first cluster, represented by the 5 words with the largest mean values.     
 


Cluster 0: Largest mean parameters in cluster 

Word    |    Mean    |    Variance
--- | --- | ---
minister  |  7.57e-02  |  7.42e-03
election  |  5.89e-02  |  3.21e-03
party     |  5.89e-02  |  2.61e-03
liberal   |  2.93e-02  |  4.55e-03
elected   |  2.91e-02  |  8.95e-04


Cluster 1: Largest mean parameters in cluster

...
...
