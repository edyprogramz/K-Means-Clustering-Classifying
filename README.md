*K-MEANS CLUSTERING*

## Table of Contents

- [How It Works](#how-it-works)
- [What are Cetroids](#what-are-cetroids)
- [Calculations](#calculations)
- [Conclusion](#conclusion)



## How It Works
*K-MEANS CLUSTERING*

- We don't have to give labels for our data points.
- All we do is give the features that make up a data point.

![Web capture_21-6-2023_82738_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/c0630cfb-4a7a-4353-a26a-2d9ebb34c4a3)

- anything in brown side is part of the brown class. Same applies to all the other classes (blue, gray, pink, red, yellow,.etc)
- The white X<sup>'s</sup> , represent **cetroids**

## What are Cetroids?

Centroids are the mean/average of all the data points assigned to a particular cluster.

Centroids are placed randomly on our graph.

![Web capture_21-6-2023_8182_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/b784e73d-7e8d-46c0-a433-017d81341ebb)

- The number of centroids depends on the number of K

- if k = 2, then centroids will be = 2

![Web capture_21-6-2023_81836_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/adff8668-ae16-4002-8a9a-abd196097e2f)

![Web capture_21-6-2023_81727_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/66a61c6b-d404-4b97-9157-27b0ff589c55)


- since centroids are placed randomly; our computer continually places them randomly across the graph, until it gets to a point when the data points stops changing.

## Calculations

- Cetroids are placed in the middle of the cluster as shown below:

![Web capture_21-6-2023_82127_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/ed491724-7aae-4b1b-9660-8ce59620ae34)

Average = (X<sub>1</sub> + X<sub>2</sub> + X<sub>3</sub>) / number of points

- in this claculation we are finding the average
- we add up all the points / divide by the no of points

![Web capture_22-6-2023_11455_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/ab797016-2b73-457b-9bfe-4428f4e359b2)

NOTE: *our computer continually places them randomly across the graph, until it gets to a point when the data points stops changing.*

![Web capture_22-6-2023_11648_www youtube com](https://github.com/edyprogramz/K-Means-Clustering-Classifying/assets/116636391/200e78d4-b38c-4ec8-8d59-c83e7d3604bc)

## Conclusion

- This may be abit slower based on the size of features.



