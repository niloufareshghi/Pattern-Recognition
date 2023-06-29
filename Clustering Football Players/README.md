There are thousands of professional football players across the world, each with specific skills and unique playing style. Given their quantitative playing attributes, however, it might be possible to determine players with similar playing styles, and find groups of players with (almost) identical qualities.
To accomplish this task, we make use of FIFA 23 player ratings. The dataset contains the information corresponding to over 18000 football players, each with 87 various features. Our goal is to investigate how these players can be assigned to distinctive clusters.
First, we assume the players with a rating above 85 (91 players in total), and discard all non-numeric features.

a. Normalize the data, and apply PCA to them so that the dimensions are reduced to 2.

b. Assuming k = 5, perform k-means clustering. Visualize clusters with players’ names attached to each point.

c. Is Kylian Mbappé playing style more comparable to that of Lionel Messi or Cristiano Ronaldo? How about Mehdi Taremi?

Now, we wish to see how accurate this approach is in categorizing football players based on their positions. As can be seen in the dataset, each player is given a ‘Best Position’ attribute, denoting his most preferred position on the pitch.

d. Perform clustering on all the players with k = 16 (since there are 16 distinct positions lis
