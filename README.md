# CPSC4310-ML
Repo for CPSC4310 - Machine Learning Spring 2022

FMA_Medium contains the actual tracks in mp3 format that the metadata is generated on.
FMA_Metadata contains the following CSV files about the tracks
    tracks.csv: per track metadata including ID, title, artist, genres, type, duration, language, tags and play counts, for all 106,574 tracks.
        ID, Title, Artist, genres, type, language, and tag are all stored as strings. Where as the duration and play counts are stored as integers
    genres.csv: all 163 genres with name and parent (used to infer the genre hierarchy and top-level genres).
    features.csv: common features extracted with librosa.
    echonest.csv: audio features provided by Echonest (now Spotify) for a subset of 13,129 tracks.
