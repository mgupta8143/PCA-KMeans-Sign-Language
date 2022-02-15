# PCA-KMeans-Sign-Language

Used Sign Language MNIST Dataset for experimental purposes. Ran K-Means to cluster different languages. Achieved 81% accuracy with 8000 clusters and 80% accuracy with 
2500 clusters. 

Standardized data, used PCA, and MiniBatch KMeans to quicken process and reduce issues from curse of dimensionality (euclidean distance becomes less useful in higher dimensions)

Improvements (assuming only using clustering/unsupervised learning)
* Could use normal KMeans (at the expense of computation)
* Could play around more with hyperparameters (variance of PCA, #clusters, #iterations per kmeans cycle)
* Could try a supserset clustering algorithm (notably Gaussian MM as an extension to KMeans using EM) (would probably do much better like >high 80s, low 90s)
* Could try using DBSCAN, Hierarchal Clustering / Other Methods
* Feature Construction?
* Use Boosting/Ensemble between many clustering algos?
* Better Normalization Technique?


