# Vignette-clustering-methods

This is a vignette focused on 3 clustering methods in R: hierarchical clustering, distribution-based clustering, and density-based clustering. They will be illustrated on an unsupervised country classification data.

# Contributors 
KunXiao Gao, Justin Liu, Ruoxin Wang, Kassandra Trejo 

# Vignette Abstract
For our topic we are specializing on three different types of clustering methods. But first let's look at what clustering is. Clustering refers to partitioning our observations from our data set into distinct groups that are similar to each other. In hierarchical clustering the main principle is that every object is connected to its neighbors depending on their distance.It is represented in a dendrogram which is an upside down tree. In density based clustering or model based methods the data is clustered based on density and not distance like in the hierarchical method. Lastly we decided to also use distribution based clustering method. This method uses an entirely different metric, probability. In this method the data is grouped based on the likelihood of belonging to the same probability distribution. We decided to utilize an unsupervised country classification data set where we implemented hierarchical clustering, density and distributional based clustering. We found that using 3 clusters in our hierarchical method provided the best results. 
# Repository Contents 
`scripts` folder includes our script and markdown files with our code and visualizations.
`img` folder includes images and png documents that we utilized in our vignette.
`data` folder includes our raw country data that we downloaded from Kaggle as well as our processed and clean data.


# References
For further references on the clustering methods mentioned in this report there are many websites and textbooks that provide extensive information on these topics and here are a few that we accessed to help us:

- [Model-based clustering: an introduction to Gaussian Mixture Models (video)](https://youtu.be/h7RVeO-P3zc)
