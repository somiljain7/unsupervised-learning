function and keywords
1)crosstab()

2)standardScaler() -> transforms each feature to have mean 0 and variance 1
                      Standardscaler is apreprocessing step
3)MaxAbsScaler

4)Normalizer->Normalizer() rescales each sample -The Normalizer will separately transform each company's stock price to a relative scale before the clustering begins. 

5)t-SNE- created a 2d map of dataset(t-distributed tochastic neighboe embedding)(approximately representing the distances between the samples)

6)hierarchial clustering 
every centroid(data unique) begins in a separate cluster , at each step the 2 closest clusters are merged
and continue to unite all unique datapoints in a single cluster.this is agglomerative hierarchial clustering

7)dendrogram

8)linkage

9)merging

10)in a "complete" linkage : distance between clusters is max. distance between their samples
specified via method parameter

11)fcluster()
returns a Nuumpy array of cluster labels

12)t-SNE has only fit_transform()
has a fit_transform() method ,simultaneously fits the model and transforms the data,has no separate fit() or transform() methods,cant expend the map to include new data saamples,must start over each time
learning rate(50-200)

13)DIMENSION REDUCTION
IT FINDS PATTENRS IN DATA AND USES THESE PATTERNS I DATA AND USSES THESE PATTERNS TO RE EXPRESS IT IN A COMPRESSED FORM

14)PRINCIPAL COMPONENT ANALYSIS(FUNDAMENTAL DIMENSION REDUCTION TECHNIQUE)

15)PCA - aligns data with axis
  rotates data samples to be aligned with axes
  shifts data samples so they have mean 0
  
16)pearson correlation - measures linear correlation of features 
 -1,1 -> valyes range
 value 0 means no linear correlation
 
 17)PCA - learrns directions if variance
 
18)
