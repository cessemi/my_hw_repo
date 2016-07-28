I know you mentioned you were looking at a few data sets. Is there one data set or can you combine a couple of them to give you many different users which give you 5-6 features (genre, artist, length of song, possibly even the location of where the song was played) about the music that each user listens to? From that you can use a model like KNN to be able to suggest similarity based music to new users, given what other people prefer. Ratings, or some other form of feedback from the users, can be huge when using KNN. Another algorithm, which may be very useful, is K-means clustering (https://en.wikipedia.org/wiki/K-means_clustering) this will let you essential plot all of your data and cluster them together, where you can ultimately take the most densely populated clusters and create a 'playlist' out the songs within them.