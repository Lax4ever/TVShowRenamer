README

Very basic program. Used to rename TV Show video files to a format that is friendly for the Plex Media Server.

Please be aware of the following:

1) Make sure your episodes are already separated by season
2) Each season folder should only have the episode video files and their sub files
3) Each episode, at this time, can only have one sub file, unless it is an .idx and .sub pair
4) The Renamer does not currently know how to handle multi-part, single file episodes.

Supported video extensions: ".mp4",".m4v",".flv",".mkv",".mov",".avi",".mts",".mpeg",".wmv",".mpg",".h264",".3g2",".3gp",".rm",".swf",".vob"
Supported subtitle extensions: ".sub",".srt",".sbv, .idx"

If .idx subtitle files are present, make sure there is a corresponding .sub file.

Renamer will ignore any file that doesn't have those extensions

Usage Instructions

1) Open the program with either the Python script, or the executable if Python is not installed
2) Click the "Browse" button and find your season folder
3) Enter a Show Name and select the correct Season Number
4) Click the "Get" button
5) Episode details (before and after) will show in the Comparison Panel
6) Click Start to finalize

Clear button can be used to clear the "Get" results if the conversion does not line up right

Test button will only work with Python script, as the results of that button print only to a console window