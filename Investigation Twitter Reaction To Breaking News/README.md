Twitter is a rich source of data for opinion mining,
sentiment analysis and truth discovery. However, one of
the biggest problems which many Twitter-based
applications encounter with is data redundancy caused by
the fact that Twitter users often post similar tweets (e.g.
using retweet function) when it comes to popular topics
and events. Therefore, clustering similar tweets together
would definitely produce more accurate results.
We take into consideration a series of tweets posted
during the Boston Marathon Bombing event in April 15,
2013. During this terrorist plot, misinformation spread
widely despite efforts by users and experts to correct
rumors which were inaccurate.
In order to compare different tweets and measure their
dissimilarity, we consider Jaccard distance. Given two sets
A and B, Jaccard index is defined as the size of the
intersection divided by the size of the union of their
samples.

Then the Jaccard distance can be obtained by subtracting Jaccard index from 1

To use this metric, a tweet must be considered as a set of words such as {a,b,c}. This metric takes values between 0 and 1, and returns
smaller values for more similar and larger values for less similar tweets, while it is 0 if the tweets
are identical and 1 if they don’t have any common word.

a. Use the provided initial centroids and cluster the tweets in K = 25 clusters. The output must
be a file which contains the clustering results such that each line represents a cluster in the
form of: cluster_id: a list of tweet IDs which belong to this cluster. Include this file in your
report.

b. Design and implement an efficient method to find the K initial centres so that K-Means can
generate good clustering results similar to the results you obtained in the previous part.
