# Spotify Music Recommender using Logistic Regression

This project implements a music recommender system using logistic regression. The system predicts a user's likelihood of repeatedly listening to a song within a set timeframe based on various audio features provided by the Spotify API.

## Data Features

- **Acousticness**: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
- **Danceability**: Describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
- **Duration_ms**: The duration of the track in milliseconds.
- **Energy**: A measure from 0.0 to 1.0 representing a perceptual measure of intensity and activity.
- **Instrumentalness**: Predicts whether a track contains no vocals.
- **Key**: The key the track is in.
- **Liveness**: Detects the presence of an audience in the recording.
- **Loudness**: The overall loudness of a track in decibels (dB).
- **Mode**: Indicates the modality (major or minor) of a track.
- **Speechiness**: Detects the presence of spoken words in a track.
- **Tempo**: The overall estimated tempo of a track in beats per minute (BPM).
- **Time_signature**: An estimated overall time signature of a track.
- **Valence**: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.

## Target Variable

- **Liked**: 1 for liked songs, 0 for disliked songs.

