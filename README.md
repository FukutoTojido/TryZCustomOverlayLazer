# TryZCustomOverlayLazer
A gosumemory overlay inspired by the upcoming UI of osu!lazer. Only support for osu!Standard currently and haven't been tested for In-game Functionality.

This overlay can fetch the data of your current osu! Bancho account, as well as the current map leaderboard. The accent colors of the overlay are taken from your profile picture. The overlay itself is the source code. If you wish to modify anything, go ahead. But I won't give any support for your modification, you are on your own.

## Prerequisite
- [gosumemory](https://github.com/l3lackShark/gosumemory)

## Installation Guide:
- Download the latest zip file from the [Release page](https://github.com/FukutoTojido/TryZCustomOverlayLazer/releases)
- Extract the zip file and copy it to the `static` folder of `gosumemory`. \
  ⚠⚠⚠ **The content of the zip file should be in a folder called TryZCustomOverlayLazer** ⚠⚠⚠
- Create a Browser Source on OBS, set the Width to 1920, Height to 1080, and the URL to **http://127.0.0.1:24050/TryZCustomOverlayLazer**

## FAQs
- **Q: Why my profile picture and data aren't fetched and shown on the client?**

  Due to the "server" location, the response waiting time may vary. Therefore, it might take a long time for the response to be received by the overlay. If you have waited long enough and the overlay hasn't changed, you can try refresh your Browser Source on OBS. If that also doesn't work, it could be a server-side error, which should be reported to me.

- **Q: The Browser Source shows nothing.**

  First, check your Browser Source URL again. Next, check your overlay folder's name in the `static` folder of `gosumemory`.
  
- **Q: The leaderboard is broken!**
  
  If you refresh the Browser Source at the middle of a gameplay, the leaderboard won't be fetched. Retry the map will fix this issue. If that doesn't help, try refresh your Browser Source. And if that also doesn't help, it could be a server-side error (again), which should be reported to me.
 
- **Q: I want to disable the leaderboard**
  
  Just head to the `config.json` file and set the `leaderboardEnable` option to `0`. Then refresh your Browser Source. If that doesn't help, refresh the cache of your Browser Source in its Properties. And if the overlay still doesn't change, blame OBS.
  
- **Q: Can this be used for a streaming session?**
  
  Surely! You can have a look at it on [my stream](https://www.twitch.tv/videos/1715056556)
  
## Screenshots
![https://i.imgur.com/1nOYx7w.jpeg](https://i.imgur.com/1nOYx7w.jpeg)
![https://i.imgur.com/II2gdn4.jpg](https://i.imgur.com/II2gdn4.jpg)
