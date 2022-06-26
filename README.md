# DayZServerBAT
This is a fully automated batch script for running and updating a DayZ server and its mods.

This batch script is initially based on [TheGamingChief's tutorials @ YouTube](https://www.youtube.com/playlist?list=PLb-LObGTjjRmbOwcQfuORIL6NKX4Jon2W), but with more options.

***

### The main changes compared to the [TheGamingChief's](https://www.youtube.com/TheGamingChief):

* ***The BIGGEST addition is a script that generates an external script file on every run for SteamCMD to update mods, which allows for using a single login session for the full list, therefore eliminating the frustrating issue of getting blocked by Steam for spamming the server.***
* A separate modlist file for server-side-only mods.
* Option to skip updates at the beginning - good for when restarting to apply changes.
* More variables at the top to eliminate the need to edit the code itself:
    - Server profile folder (ServerProfile)
    - Server port (ServerPort)
