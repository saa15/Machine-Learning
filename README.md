Implementation of K-Means Algorithm using Euclidean distance on a dataset with 2 attributes.

Initialization:
Based on the input parameter(k), you should randomly select k points as centroids.

Termination Condition:
The usual termination condition in k-means is when the centroids no longer more. In this
assignment, you should also limit your update step to a maximum of 25 iterations.

Input:
The input file will be specified by the parameter <input-file-name>.
Sample Input for the KMeans.java file: 
<K-value> <input_filename> <output_filename>
100 "SampleInputDataSet.txt" "SampleOutputObtained.doc"

Output:
<cluster-id> <List of points ids separated by comma>
For example,
1       2, 4, 7, 10

Validation:
The usual method of evaluating the goodness of clustering will be used. It is the Sum of
Squared Error function, defined as:
SSE = ΣΣ dist(mi,x) * dist(mi,x)
mi is the centroid of ith cluster
Results.doc contains the SSE values 
