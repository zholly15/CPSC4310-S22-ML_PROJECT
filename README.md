# CPSC4310-ML
Repo for CPSC4310 - Machine Learning Spring 2022
## The audio files
FMA_Medium contains the actual tracks in mp3 format that the metadata is generated on. We have these if we wish the analyize the mp3 files themselves and so we can actually play the songs in the notebook. As of right now we are not using 
these files in preprocessing or in any classification
## The meta data
FMA_Metadata contains the following CSV files with information generated from the tracks or information about the track
### tracks.csv
This contains per track metadata including ID, title, artist, genres, type, duration, language, tags and play counts, for all 106,574 tracks.
    ID, Title, Artist, genres, type, language, and tag are all stored as strings. Where as the duration and play counts are stored as integers. There is currently empty string values for some of the string values since those values do not exist
### genres.csv
 all 163 genres with name and parent (used to infer the genre hierarchy and top-level genres). These are all stored as strings
### features.csv
common features extracted with librosa. This is what we believe to be the most useful data as we classification genre of songs. These are integer values of various musicial features of the data.
### echonest.csv
audio features provided by Echonest (now Spotify) for a subset of 13,129 tracks. This are numerical values of different "moods" of the song such as dancibility. We are currently not using this in our classifications but
it is included as part of the data set.
