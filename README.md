# Analyzing Cryptocurrencies using Unsupervised Machine Learning

## Overview

A dataset of cryptocurrencies will be analyzed using Unsupervised Machine Learning algorithms to discover trends in order to 
convince the firm Accountability Accounting to invest in these new currencies. <br/>
The provided dataset has 1252 rows and it needs to be cleaned and encoded in order to use it for applying PCA. <br/>
After the data was cleaned PCA was implemented so we can cluster the cryptocurrencies using K-Means.<br/>
Finally the result was plotted in a 3D and 2D graph to visualize our results.

## Results 

#### Original Dataset

![](resources/images/orig-df.jpg)

#### Cleaned Dataset

![](resources/images/clean-df.jpg)

#### Implementing K-means

* Finding the number of clusters and then applying K-means to cluster the data

![](resources/images/elbow.jpg)

* DataFrame clustered

![](resources/images/clusted-df.jpg)

#### Plotting the tradable cryptocurrencies

![](resources/images/3d.jpg)

![](resources/images/2d.jpg)



