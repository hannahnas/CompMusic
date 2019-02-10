# Computational Musicology Portfolio

### Research question: What features are important for classifying a song to a specific genre?

### Method
First, I will download spotify playlists for the genres jazz, rock and R&B and look at the features.
Then I might try to train a classifier that returns feature importance.

### First look at the data
Spotify playlists: Jazz Classics, Rock classics, RNB Classics

|          |Mean energy| Mean danceability| Mean loudness|Mean acousticness|Mean tempo|Mean instrumentalness|
|---------:|---------:|---------:|--------:|--------:|--------:|---------:|
|Jazz      | 0.23163|  0.4689| -17.46062| 0.80506| 107.8041| 0.5209499|
|Rock      | 0.7236467| 0.5338133| -8.35904| 0.168123| 121.7946| 0.0488746|
|R&B       | 0.6366574| 0.751213| -6.392676| 0.1393125| 109.8152| 0.0040193|
