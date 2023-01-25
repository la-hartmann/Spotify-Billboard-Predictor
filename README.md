<b>Context</b>

The purpose of this project was to perform descriptive and inferential statistical analysis using  Spotify APIs of over 15,000 songs. Songs were analyzed from three decades (1990s, 2000s, and 2010s) to determine which song features are correlated with Billboard success, and which model can be constructed from these features with the best accuracy.

<b>Tableau Presentation:</b>

To view the presentation associated with this Jupyter Notebook, please refer to my Tableau Public profile: [Spotify Hit Predictor](https://public.tableau.com/views/SpotifyHitPredictor_16699489003420/story?:language=en-US&:display_count=n&:origin=viz_share_link)

The Spotify Hit Predictor slide deck reviews key findings from the analysis performed using Python. Another walk through of this can be found on the Tableau Public profile and is labeled 'Spotify Hit Predictor Visuals'.

<b>Schema:</b>

This is a [dataset](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset) broken up into separate tables by decade consisting of features for tracks fetched using Spotify's Web API. The tracks are labeled '1' or '0' ('Hit' or 'Flop') depending on some criterias of the author.
(Note: The author does not objectively considers a track inferior, bad or a failure if its labeled 'Flop'. 'Flop' here merely implies that it is not a song that probably could not be considered popular in the mainstream.)

<b>Acknowledgements:</b>

- "spotipy": Python module for Spotify's API (https://pypi.org/project/spotipy/)

- "billboard": Python module for Billboard's API (https://pypi.org/project/billboard.py/)
 
- Spotify, the company itself. For keeping a database of such in-depth details of every track in their library. And for exposing their API for the world to use.

<b>Attributes:</b>

For further reading/description of Spotify APIs:
(https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)
