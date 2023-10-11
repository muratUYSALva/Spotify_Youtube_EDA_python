## About Dataset

This repository contains a dataset of songs by various artists worldwide, including detailed information about each song, as well as their performance on Spotify and YouTube.

### Content

The dataset includes 26 variables for each song collected from Spotify. These variables are briefly described below:

- **Track**: The name of the song, as visible on the Spotify platform.
- **Artist**: The name of the artist.
- **Url_spotify**: The URL of the artist on Spotify.
- **Album**: The album in which the song is contained on Spotify.
- **Album_type**: Indicates if the song is released on Spotify as a single or contained in an album.
- **Uri**: A Spotify link used to find the song through the API.
- **Danceability**: Describes how suitable a track is for dancing based on a combination of musical elements.
- **Energy**: Represents a perceptual measure of intensity and activity.
- **Key**: The key of the track in standard Pitch Class notation.
- **Loudness**: The overall loudness of a track in decibels (dB).
- **Speechiness**: Detects the presence of spoken words in a track.
- **Acousticness**: A confidence measure of whether the track is acoustic.
- **Instrumentalness**: Predicts whether a track contains no vocals.
- **Liveness**: Detects the presence of an audience in the recording.
- **Valence**: A measure describing the musical positiveness conveyed by a track.
- **Tempo**: The overall estimated tempo of a track in beats per minute (BPM).
- **Duration_ms**: The duration of the track in milliseconds.
- **Stream**: Number of streams of the song on Spotify.

Additionally, there is information related to the songs' performance on YouTube:

- **Url_youtube**: URL of the video linked to the song on YouTube.
- **Title**: Title of the video clip on YouTube.
- **Channel**: Name of the channel that published the video.
- **Views**: Number of views.
- **Likes**: Number of likes.
- **Comments**: Number of comments.
- **Description**: Description of the video on YouTube.
- **Licensed**: Indicates whether the video represents licensed content.
- **official_video**: Boolean value indicating if the video found is the official video of the song.

### Notes

Please note that the data in this dataset was collected on the 7th of February, 2023. These statistics may change over time.

## Dataset Source

The dataset was obtained from Kaggle. You can find the original dataset [https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube]
