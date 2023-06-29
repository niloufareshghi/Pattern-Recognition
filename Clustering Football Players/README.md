There are thousands of professional football players across the world, each with specific skills and unique playing styles. Given their quantitative playing attributes, however, it might be possible to determine players with similar playing styles and find groups of players with (almost) identical qualities.
To accomplish this task, we make use of FIFA 23 player ratings. The dataset contains information corresponding to over 18000 football players, each with 87 various features. Our goal is to investigate how these players can be assigned to distinctive clusters.
First, we assume the players with a rating above 85 (91 players in total), and discard all non-numeric features.

a. Normalize the data, and apply PCA to them so that the dimensions are reduced to 2.

b. Assuming k = 5, perform k-means clustering. Visualize clusters with players’ names attached to each point.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/a412d74e-6052-4f5e-b66d-401225a2a6e0)


c. Is Kylian Mbappé's playing style more comparable to that of Lionel Messi or Cristiano Ronaldo?

m = int(data[data['Known As'] == "K. Mbappé"].index.values)
l = int(data[data['Known As'] == "L. Messi"].index.values)
r = int(data[data['Known As'] == "Cristiano Ronaldo"].index.values)
t = int(data[data['Known As'] == "M. Taremi"].index.values)
     

ml = dist(df.iloc[m].values, df.iloc[l].values)
print(ml)
mr = dist(df.iloc[m].values, df.iloc[r].values)
print(mr)
     
299690659.22214663
325200999.5372162
Mbappe is more similar to Leo Messi

Now, we wish to see how accurate this approach is in categorizing football players based on their positions. As can be seen in the dataset, each player is given a ‘Best Position’ attribute, denoting his most preferred position on the pitch.

d. Perform clustering on all the players with k = 16 (since there are 16 distinct positions)

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/80b90d0d-97e4-4b0f-bfe1-960fdd324850)

