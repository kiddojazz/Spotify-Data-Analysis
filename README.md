# Spotify-Data-Analysis

# Step 1: You will need to create a Spotify developer account

The developer account is needed to get certain keys and tokens.

[Spotify Developer](https://developer.spotify.com/dashboard/login)

**"endpoint"**


# Make a function that will extract all track information from IDs.

Now, that we hae the track IDs, we need to create a function that will help us get specific information about the track.

## List of features from the track ID:

- Name: Track name.
- Album: This is the album name.
- Artist: Artist name.
- Release Date: Date which the track was released.
- Length: Duration of track in millisconds.
- Popularity: Song popularity between the range of 1-100.
- Acousticness: Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic.
- Danceability: based on a variety of musical components, such as tempo,rhythm stability, beat strength, and overall consistency whether appropriate a track is for dancing.
- Energy: A perceptual gauge of intensity and activity, energy ranges from 0.0 to 1.0.
- Instrumentalness: predicts whether a song is vocal-free. Sounds like "ooh" and "aah" are regarded as instrumental in this situation. Tracks that are spoken word or rap are obviously vocal. The likelihood that a track is vocal-free increases as the instrumentalness value approaches 1.0. The intent is for values above 0.5 to represent instrumental tracks, but confidence increases as the value gets closer to 1.0.
- Liveness: Identifies whether there is a listenership in the recording. Greater liveness numbers indicate a higher likelihood that the song was performed live. A score greater than 0.8 indicates a high probability that the music is live.
- Speechiness: A feature that recognizes spoken words in music.
- Tempo: a track's estimated overall tempo expressed in beats per minute (BPM). Tempo, which in musical terms refers to a piece's speed or tempo, is directly related to the length of an average beat.
- Valence: A scale from 0.0 to 1.0 used to describe the overall musical positivity of a tune. Those with a high valence sound happier, cheerier, and more euphoric, whilst tracks with a low valence sound more depressing (e.g. sad, depressed, angry).
