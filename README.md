# Content Filtering Based Music Recommendation 
While listening to music it's normal to want to find a similar song that you are currently listening to which you may like. The most common way it is done is using Collaborative - Based Filtering where we often look for the following :
* User–item interaction data
* User IDs
* Item IDs
* Ratings or implicit feedback
* Enough overlapping user history
These features don't usually have anything to do with the actual music that is being listened to by the user. So the aim of this small project is to recommend similar songs to the song the user is currently listening to. We use cosine similarity here to find similar songs from the genre that the user is currently listening to and then we use **K- Means** Clustering to identify the closest 5 songs which we can recommend to the user.
