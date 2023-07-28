# Capstone Project 

## Introduction

In today's world, even though the original and more classic forms of listening to music (i.e. live music, vinyl, CD's) are still alive and well - and often preferred - our main way of listneing to music on-the-go is through streaming platforms of which there are many - Spotify, Apple Music, and Title are just a few. With millions of songs at our fingertips at any moment, curators in the business are trying to retain and gain new customers by actively using machine learning techniques to look for ways to organize and recommend familiar, similar, and/or new music to listeners. As more streaming platforms arise and recommender systems improve, this has become increasingly more competitive and therefore a major goal of the biggest platforms out there. My project aims to use machine learning to create a model that can classify the genre of any song based on particular characteristics. This baseline goal of predicting the genre is an important step in understanding the most powerful and distinctive attributes of music and will help us be able to better group artists and their music and from there, better understand listeners and their preferences. 

My goal will be to combine spotify datasets to create one large dataset of songs. This will include some information on the artist, album, spotify track ID, track name. My main columns of interest will be the song attributes. A description of these are listed below. 

- danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable
- energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and - - activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale
- key: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1
- loudness: The overall loudness of a track in decibels (dB)
- mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0
- speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks
- acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic
- instrumentalness: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content
- liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live
- valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)
- tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration
- time_signature: An estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). The time signature ranges from 3 to 7 indicating time signatures of 3/4, to 7/4.
- track_genre: The genre in which the track belongs


### Contents/Todo

- [X] Data Exploration 
- [ ] Data Cleaning and Preprocessing 
- [ ] Modeling
- [ ] Advanced Modeling

## References 

- https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
- https://www.kaggle.com/datasets/lilycarew/spotify-songs-information



