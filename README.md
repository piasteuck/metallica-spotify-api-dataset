# metallica-spotify-api-dataset

This dataset provides data on Metallica's music, retrieved via Spotify's API. It was inspired by [Jarred Priester's Metallica dataset](https://www.kaggle.com/datasets/jarredpriester/metallica-spotify-dataset/data), but includes more recent data and additional features.

## Data Included

- All Metallica tracks from all albums published on Spotify
- Metallica studio albums only (some have two versions, e.g., remastered and not remastered. Only one version of each has been included)

Metallica is one of the most successful bands in music history. This dataset allows for analysis of various audio features and metadata associated with their tracks. Additionally, it introduces an album popularity metric, which differs from track popularity. Album popularity reflects the overall performance of the album on Spotify, offering a broader view than individual track performance.

## Dataset Columns

- **name** – Name of the track
- **album** – Name of the album the track is from
- **release_date** – Release date of the album (YYYY-MM-DD format)
- **track_number** – Track's position within the album
- **id** – Spotify ID for the track
- **uri** – Spotify URI for the track
- **acousticness** – A confidence measure (0.0 to 1.0) indicating the likelihood that the track is acoustic
- **danceability** – A measure (0.0 to 1.0) describing how suitable a track is for dancing, based on factors such as tempo and rhythm stability
- **energy** – A measure (0.0 to 1.0) indicating the intensity and activity of the track
- **instrumentalness** – A measure (0.0 to 1.0) predicting whether the track contains no vocals
- **liveness** – A measure (0.0 to 1.0) detecting the presence of an audience, indicating if the track is likely a live recording
- **loudness** – The overall loudness of the track, measured in decibels (dB)
- **speechiness** – A measure (0.0 to 1.0) detecting the presence of spoken words. Higher values indicate more spoken-word content
- **tempo** – Estimated tempo of the track in beats per minute (BPM)
- **valence** – A measure (0.0 to 1.0) describing the musical positiveness of the track
- **track_popularity** – Popularity of the track, from 0 to 100, as determined by Spotify's engagement data
- **album_popularity** – Popularity of the entire album, from 0 to 100, calculated based on overall album performance
- **duration_ms** – Duration of the track in milliseconds

## Possible Use Cases

- **Audio feature analysis** – Compare and analyze various audio features such as danceability, energy, or acousticness across different albums or time periods
- **Album vs. track performance** – Explore differences between track popularity and album popularity to understand how individual songs perform relative to their albums
- **Music genre classification** – Use audio features to classify tracks into sub-genres of Metallica's music or metal in general
- **Album evolution** – Study how Metallica's musical style has evolved over time by analyzing the changes in audio features and popularity across albums
- **Correlation analysis** – Investigate relationships between different audio features and how they correlate with popularity (both track and album)
- **Recommendation systems** – Build or refine recommendation algorithms based on specific Metallica track attributes

## Spotify API Reference

For further information about these audio features and how they are calculated, see the official Spotify API documentation:

- [Get Audio Features](https://developer.spotify.com/documentation/web-api/reference/get-audio-features)
- [Get an Album](https://developer.spotify.com/documentation/web-api/reference/get-an-album)
