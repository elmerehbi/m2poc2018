# Exploring any relation between SST & PSAL in the Kuroshio gulf region 

* add x/y labels for the snapshot map of te clusters distribution (see at the bottom) & rename the image file
* lat/lon map of the most occuring cluster
* snapshot basemap
* bic to find optimal number of clusters (though obvious)
* apply to the whole set (at the end only)

In this work we attempt to look for any correlation between sea surface temperature (SST) and Salinity (PSAL) for the Kuroshio gulf region.


## Procedure

* Dataset used: ISAS15 dataset ([source](https://github.com/obidam/m2poc2018/tree/master/projects))


* Use the unsupervised Gaussian Mixture Model to fit and predict cluster. For this we specify we are looking for **3 clusters**, one for each of the two main clusters identified in the joint plot of the conditional probabilities and one as a `trash cluster` for the rest of the points.
* ​



## Results

A correlation between SST and PSAL was identified from the conditional probabilities as shown in the following joint plot:

![jointplot_conditional_marginal_probabilities](figs/jointplot_conditional_marginal_probabilities.png)

Below are the three identified clusters:

![cluster0](figs/cluster0.png)

![cluster1](figs/cluster1.png)

![cluster3](figs/cluster3.png)

The following map shows a snapshot map of the distribution of the three clusters 
![](./figs/sample_map_of_most_frequent_label.png)

The following map shows the most frequent cluster/label (**0**)

![](./figs/sample_map_of_most_frequent_label.png)

