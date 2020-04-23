# Extract music data from Spotify using spotipy

This small piece of code is aimed at extracting spotify music data using the spotipy, a lightweight Python library for the Spotify Web API. 

In order to extract music data from Spotify, first you have to set up a Spotify Developer Account. It is a very simple process that you can do [here](https://developer.spotify.com/dashboard/login)

Once you set up your account, you have to create a Client ID, and retrieve your Client ID and your Client Secret. These two codes, as well as your Spotify username, are requiered to get the token that allows you to retrieve music data. The steps are well explained in the spotipy documentation, available [here](https://spotipy.readthedocs.io/en/2.11.1/).

Also, in order to get familiar with the Spotify API and the endpoints you have access to, it 's very recommendable to read the [Spotify's Web API Documentation](https://developer.spotify.com/documentation/).

Having said this, this programme allows you to use the Spotify browser capabilities to search for an artist and retrieve data about the artist, their albums and their tracks. The data is directly stored in three separate pandas dataframes.

For more information, you can check the tutorial I wrote in Medium in the following [link](https://medium.com/@jcanalesluna/how-to-get-your-favourite-artist-music-data-from-spotify-using-the-python-library-spotipy-d5c25065c91e).
