**Jewelry Master** is a 2006 puzzle game by Arika, the creators of Tetris: The Grand Master. <br>
**The game is freeware and can be downloaded [here.](http://web.archive.org/web/20070629133551/http://www.arika.co.jp/arika_eng/download/down3.html)**<br>
<br>
The game required servers to function and only worked online, and the servers have been down for more than a decade. However, this patch will allow you to play the game without any internet connection whatsoever. The only thing that doesn't work is replays, as they require an internet connection.
<br>
<br>
# Technical Notes
The game expects the server response to be "0" upon a successful login, this patch forces the "received" response to always be 0, bypassing authentication and allowing the game to be played. Additionally, several strings used in-game were encoded in Shift-JIS characters and have been converted back to ASCII to display correctly on non-Japanese locales.<br>
# Installation
To install, extract the zip file to your JM folder. Make sure to replace the executable when asked.<br> No username or password is needed, just log in.
# Credits
Shoutouts to [Pancakes](https://github.com/patapancakes), who helped me dissassemble the game and write the patch.
