### spotify-songs-analysis

This is the final project for stats101a spring20 from UCLA taught by professor [Robert Gould](http://www.stat.ucla.edu/~rgould/Home/About_Me.html) and TA Xinzhou Ge
The dataset we will be using can be found at [processed_dataset.csv](https://github.com/dchen236/spotify-top50-popular-song-analysis/blob/master/data/processed_dataset.csv). 

We adapted the [dataset from kaggle)[https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db] containing songs of 27 genres.

### Team Member
- Danni Chen
- Yufeng Zhang

### Data Codebook 

#### CSV files

- [SpotifyFeatures.csv.zip](https://github.com/dchen236/Stats101a-Final-Project/blob/master/data/SpotifyFeatures.csv.zip) the original dataset from Kaggle in zipped format. 
- [equally_sampled_songs.csv](https://github.com/dchen236/Stats101a-Final-Project/blob/master/data/equally_sampled_songs.csv): we sampled 100 songs from each genre, thus this dataset contains 2700 songs.

#### Attributes
There are 14 attribuets we used in our analysis (equally_sampled_songs.csv)

Numerical
- popularity: popularity of the song
- acousticness: acousticness of the song, 0-1 indicates how confidence Spotify thinks this songs is acoustic, higher value means the song is more likely to be acoustic.
- danceability: dancibility, higher means easier to dance to the song
- durations_s: duration of the songs in seconds
- energy: energy of the song, higher means more energetic 
- instrumentalness, the closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content.
- liveness: liveness of the song, higher means the song is likely to be a live recording
- loudness: loundness of the song, the higher the lounder
- speechiness: speechness of the song, the higher the value, the more spoken word the song contains. 	Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.
- tempo: 	The overall estimated tempo of a track in beats per minute (BPM). 
- valance:  valence of the song, higer means positive mood such as happy, cheeful, lower means negative mood such as sad, angry and depressed. 

Categorical 
- genre: Genre of the song (27 unique genres in this dataset)
- key: The estimated overall key of the track, such as A, A#, B, C, C# etc. (12 unique keys in total)
- mode: The modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.



All attribuets are defined by Spotify, details are available at [Spotify for Developers](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/) 


