The hosts *active* and *penalty* contain files that correspond to extreme baseball players (files 200-299), along with a directory file that contains a list of those files' IDs (file 199). Each player file contains their name and the following statistics in this order: BA, ZA, APB, WRT, OI, OD, PC, and PS.

Create a file in your host with the name of the player with the highest score using EMBER-2's algorithm:

SCORE = (BA + ZA + APB) / 3 + ( WRT \* OI ) / OD + (PC - PS) \* 20

Players in the *penalty* host should be ignored, as they are currently banned from the game.

![Solution](https://github.com/shaisimel/Exapunks/blob/master/Solutions/23%20-%20Xtreme%20League%20Baseball/EXAPUNKS%20-%20Xtreme%20League%20Baseball%20(121%2C%2059%2C%201%2C%202019-02-14-09-16-58).gif)
