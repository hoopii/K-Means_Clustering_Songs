# Clustering Songs with K-Means
Using K-Means Clustering to generate mood based playlists using audiofeatures from Spotify

## Use Case
I am working as a Data Scientist for Moosic, which is is a little start up that creates curated playlists done by music experts and specialists in old and new trends. 
The curated playlists all encapsulate a certain “mood” or “style”. My task is to use Data Science to add a degree of automatisation to the creation of playlists and to create an an initial prototype of a working model that clusters songs based on these audiofeatures.

## Goal: 
Create initial prototype model that clusters 5000 songs based on audiofeatures from Spotify using K-Mans

## Dataset: 
Dataset collected from the Spotify API containing contains the audio features (tempo, energy, danceability etc.) for a around 5.000 songs.
- [Here you find the file with description of audiofeatures](../main/audiofeatures_description.pdf)
- [Spotify Website: Where to get the audiofeatures](https://developer.spotify.com/discover/)

## Skills / Methods
- Use a basic clustering algorithm such as K-Means to divide the dataset into a few clusters (which will become playlists). 
- Implementation in Python and sciki-learn (https://scikit-learn.org/stable/)
- visualization with matplotlib and seaborn. 
- Data Handling mainly with pandas

## Basic Steps in this Project: 
1. Read, clean and explore data
2. Feature Selection
3. Scaling 
4. Decide on the number of clusters
5. Fit and apply K-Means
6. Explore the resulting clusters
7. Explore solution in combination with PCA 

## Assess the question: 
Is K-Means a good method to create playlists? Would you stick with this algorithm moving forward, or explore other methods to create playlists?
