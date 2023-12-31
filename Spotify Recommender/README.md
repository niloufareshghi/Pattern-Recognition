If you are a fan of Spotify, you are probably familiar with its ‘Discover Weekly’ feature. Every Monday, Spotify releases a playlist of 30 songs personalized for each user based on their music taste. These lists are often highly praised by the listeners for their accuracy, and over one-third of all new artist, discoveries happen through the recommendations made by this service. But how can people’s taste in music be assessed?
You are provided with a dataset containing the top 600 most Iranian music tracks played in the year 1399. The goal is to analyze the data and design a simple music Recommender System.

a. Calculate the mean of each attribute, and discuss the results. Is it reasonable to conclude that these tracks tend to be happy based on ‘energy’, ‘danceability’, and ‘tempo’ features?

b. Calculate the variance of each attribute. Do the listeners have similar patterns in their music preference based on solely the ‘liveliness’ feature?

c. Assuming a normal distribution for each attribute, display the estimated distribution as well as the histogram associated with each feature, and determine which one actually fits.

d. Calculate the Pearson correlation coefficient for each pair of numerical features. Which features can be safely removed based on their correlation with the others? Remove these features from the dataset.

e. Scale all the numerical features to the same range, then repeat the previous parts. Does it change the previously calculated results? Justify your answer.

f. Assuming that all the features have the same importance to the listeners, design a recommender system and obtain the top five tracks. Explain your method.

g. One approach to recommending new tracks to the users is to multiply each sample by a weight vector and find the top recommendations based on the sorted results. Through this, people’s specific preferences can be taken into consideration. Implement this strategy and find a list of top tracks that have more danceability and energy with low liveness and acoustics. As expected, the danceability and energy of the recommended tracks have higher values than the mean values, whereas the reverse is the case with liveness and acoustics.
