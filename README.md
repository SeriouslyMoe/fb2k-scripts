# fb2k-scripts
personal scripts for foobar2000
## Playback State display
Playing: &#9658; Holland, 1945 by Neutral Milk Hotel

Paused: Neutral Milk Hotel | foobar2000

`$if(%ispaused%,%album artist% | foobar2000,$char(9654) %title% by %artist%)`
## _Properties_ dialog
Standard fields:
```
Track Title=TITLE;Title Sort=TITLESORTORDER;Romaji Title=TITLEROMAJI;English Title=TITLEENGLISH;Artist Name=ARTIST;Artist Sort=ARTISTSORTORDER;Romaji Artist=ARTISTROMAJI;English Artist=ARTISTENGLISH;Composer=COMPOSER;Album Title=ALBUM;Album Sort=ALBUMSORTORDER;Romaji Album=ALBUMROMAJI;English Album=ALBUMENGLISH;Album Artist=ALBUM ARTIST;Album Artist Sort=ALBUMARTISTSORTORDER;Romaji Album Artist=ALBUMARTISTROMAJI;English Album Artist=ALBUMARTISTENGLISH;Publisher=PUBLISHER;Catalog=CATALOG;Country=COUNTRY;Media Type=MEDIATYPE;Format=FORMAT;Date Added=DATEADDED;Release Date=RELEASEDATE;Date=DATE;Event=EVENT;Genre=GENRE;Style=STYLE;Product=ORIGIN;Product Type=ORIGINTYPE;Track Number=TRACKNUMBER;Total Tracks=TOTALTRACKS;Disc Number=DISCNUMBER;Total Discs=TOTALDISCS;Wallpaper ID=WALLID;Comment=COMMENT;
```
