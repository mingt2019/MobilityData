# Twitch-Dataset

This datset contains the data collected from Twitch (https://www.twitch.tv) from Oct. 05, 2017 to Oct. 21, 2017. 
Each sample contains the following information:
- user_id
- language: language of the stream
- game_id
- started_at: the time when the stream started (in UTC)
- type: type of the stream
- stream_id
- viewer_count: the number of viewers in real time
- historical_viewer_count: the total number of viewers who have watched the streams by the streamer

The mapping from game_id to the title of the game is provided in GameTitle.txt.
The python code for collecting the dataset is provided in AutoCollection.py.

The entire dataset is available at https://drive.google.com/drive/folders/0B9swtVpmP5t4SFZCU0NlVFlqRUU?usp=sharing

If you use this dataset or the python code for reasearch, please cite the following paper:
M. Tang and J. Huang, “How to Earn Money in Live Streaming Platforms?-A Study of Donation-Based Markets,” Proc. IEEE International Conference on Computer Communications (INFOCOM), Paris, France, Apr. 2019.
