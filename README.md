# AnkiHanziTable

![image](https://github.com/Jesper-Andersson/AnkiHanziTable/assets/5511771/c72e5eb3-6d2d-4478-8ecf-a9a221d94f63)

Fork of AnkiKanjiTable for use with Chinese Hanzi.
https://github.com/AustinHasten/AnkiKanjiTable

Data from Hanzi Stats
https://ankiweb.net/shared/info/181243826

Visualize your progress by seeing your hanzi cards in a pretty table with their maturity indicated by their color.

Hanzi Fork todo:

* Additional Data (HSK, Simplified)
* Better alternative to MDBG
* Fix font errors with traditional

Notes:

* You can click on a cell to open that hanzi's details in MDBG.
* You can right click on a cell to get more options, like opening the card in the Anki Browser window, etc.
* If the field you select has more than one hanzi in it, a tile will be created for each of those hanzi. If the same hanzi is found on multiple cards, the longest interval on those cards will determine the color of the card. i.e. if you have a card with "作家" with an interval of 1 day and a card with "国家" with an interval of 1 week, the tile for "家" will use the interval of 1 week to determine its color.
* When using Group By, any hanzi that are in the selected list that you do not have cards for will appear with a black background and red foreground.
* The Filter setting uses the same search format as Anki's Browser window (https://docs.ankiweb.net/searching.html)
* The "Time Travel To" option shows what the table would have looked like at a specific point in time. If you set it to Jan 1 2020, the table should look like what it would have on that date. It can be fun to look back on your progress.
* The PNG Quality slider is a bit esoteric right now but just raise it if the PNG is not sharp enough. It controls each table cell's resolution in the resulting PNG and ranges from 25px\*25px to 200px*200px.
* The "Smooth" option just adds linear interpolation between the colors to smooth them out.

Inspired by [Kanji Grid](https://ankiweb.net/shared/info/909972618) (See here for a color key)
