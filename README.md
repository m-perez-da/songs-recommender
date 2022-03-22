![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)


# Project title: Song recommender of the 80's

### Description

Collection of several labs. The goal is to achieve a song recommender, suggesting a similar song to the one the user inputs.

This project uses web scraping, API's and clustering techniques for classification.


### Partial tasks

L6.02 file - Use of BeautifulSoup (Python library) for web scraping and collect almost 2000 songs of the 80's from:

https://playback.fm

https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number-one_singles_of_the_1980s

L6.03 file - Read a Spotify playlist using API, and extracting audio features of this songs. 

L6.04 file - Use of BeautifulSoup to scrap Spotify and add audio features to every song included in song's repository. 

L6.05 file - Use of unsupervised learning (KMeans) to create clusters of songs, based on audio features. Test of Agglomerative clustering for the same purpose.

L6.06 file - Song recommender. If a user inputs a song that is already in the repository, the recommender reads the cluster that song belongs to and recommends a song from the same cluster to the user. If the song is not part of the repository, after downloading its audio features from Spotify and check what cluster corresponds to this new song, the recommender suggest a similar song from the same cluster. 
