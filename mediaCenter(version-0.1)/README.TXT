The prototype version 0.1 for Solxiom MediaCenter.
This version works only under command line and there is no GUI. Although the Ubuntu version is only tested, but it should works under Windows too.
You can start the MediaCenter by typing "java -jar MediaCenter.jar" in your terminal/CMD prompt.
How to use this prototype: 
example
-1  \..
 0 - Video : 127 Hours
 1 - Video : 15 Till Midnight
 2 - Video : 5 Days Of August
 3 - Video : A Kiss Of Chaos
 4 - Video : Age Of Heroes
 5 - Video : Amelia
 6 - Video : Another Earth
 7 - Video : Answers to Nothing

For navegating to folders or streaming items type the number of the movie or folder in the list: "3" the movie "A Kiss Of Chaos" will be streamed into your VLC player.If you need info for an item (Movie or TvShow) you should use -i parameter with your command : "4 -i" this will retrieve the Info for "Age of Heroes". For going back to parent folders use -1. 
