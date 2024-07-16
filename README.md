# Most Streamed Spotify Songs 2024 - Model Training

This project involves training multiple machine learning models to predict the "All Time Rank" of tracks based on various streaming and playlist metrics. The dataset contains information about the tracks, including streaming counts, playlist counts, and other relevant features.

## Dataset

The dataset contains the following columns:
- `Track`
- `Album Name`
- `Artist`
- `Release Date`
- `ISRC`
- `All Time Rank` (Target Column)
- `Track Score`
- `Spotify Streams`
- `Spotify Playlist Count`
- `Spotify Playlist Reach`
- `Apple Music Playlist Count`
- `AirPlay Spins`
- `SiriusXM Spins`
- `Deezer Playlist Count`
- `Deezer Playlist Reach`
- `Amazon Playlist Count`
- `Pandora Streams`
- `Pandora Track Stations`
- `Shazam Counts`
- `Explicit Track`

## Requirements

The following Python libraries are required to run the project:

- pandas
- scikit-learn

You can install these libraries using pip:

```sh
pip install pandas scikit-learn
