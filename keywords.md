function and keywords
1)crosstab()

2)standardScaler() -> transforms each feature to have mean 0 and variance 1
                      Standardscaler is apreprocessing step
3)MaxAbsScaler

4)Normalizer->Normalizer() rescales each sample -The Normalizer will separately transform each company's stock price to a relative scale before the clustering begins. 

5)t-SNE- created a 2d map of dataset

6)hierarchial clustering 
every centroid(data unique) begins in a separate cluster , at each step the 2 closest clusters are merged
and continue to unite all unique datapoints in a single cluster.this is agglomerative hierarchial clustering

7)dendrogram

8)linkage

9)merging

10)in a "complete" linkage : distance between clusters is max. distance between their samples
specified via method parameter

11)
