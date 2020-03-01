# Steam VR Statistics
Determines all VR only games on Steam, the appid and the number of players. The required information was obtained from store.steampowered.com and steamcharts.com using the requests and lxml library. The information is stored in a sqlite database and evaluated with Matplotlib. The July 2019 was not included in the evaluation because the data show unusual values that differ significantly from the rest. I suspect the data was incorrectly output by the Steam API at that time.
![AVR VR Players](https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/avg_players.png)
![AVR VR Players](https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/peak_players.png)