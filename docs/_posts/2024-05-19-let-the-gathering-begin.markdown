---
layout: post
title:  "Let the Gathering Begin"
date:   2024-05-19 09:00:00 -0500
categories: hammurabi
---

# Hammurabi

For Christmas one year, my father gave me a copy of [BASIC Computer Games](http://www.vintage-basic.net/games.html) by David H. Ahl.
I spent many hours typing code into our TRS-80, and the game Hammurabi is one that I still remember fondly.
Evidently, I am not alone, as others have [ported the game](https://github.com/coding-horror/basic-computer-games/tree/main/43_Hammurabi) to other languages, and there are [many variants](https://www.mobygames.com/group/9512/the-sumer-game-variants/) written over the years.

I wish to preserve yet another copy of the original BASIC source, as well as port it to C#.
There is already a [perfectly fine port](https://github.com/coding-horror/basic-computer-games/tree/main/43_Hammurabi/csharp), but I want to use this as practice before attempting to port other, more complex games.

To test the code, I downloaded a copy of [Vintage BASIC](http://www.vintage-basic.net/download.html) for MacOS and installed it:

    cd ~/junk
    wget http://www.vintage-basic.net/downloads/vintage-basic-1.0.3-macos-x64.zip
    unzip vintage-basic-1.0.3-macos-x64.zip
    mv vintage-basic-1.0.3/bin/vintbas ~/bin

Then, in the directory with the `hammurabi.bas` file (`vintage/hammurabi`):

    vintbas hammurabi.bas

```
                                HAMURABI
               CREATIVE COMPUTING  MORRISTOWN, NEW JERSEY



TRY YOUR HAND AT GOVERNING ANCIENT SUMERIA
FOR A TEN-YEAR TERM OF OFFICE.



HAMURABI:  I BEG TO REPORT TO YOU,
IN YEAR 1 , 0 PEOPLE STARVED, 5 CAME TO THE CITY,
POPULATION IS NOW 100 
THE CITY NOW OWNS  1000 ACRES.
YOU HARVESTED 3 BUSHELS PER ACRE.
THE RATS ATE 200 BUSHELS.
YOU NOW HAVE  2800 BUSHELS IN STORE.

LAND IS TRADING AT 18 BUSHELS PER ACRE.
HOW MANY ACRES DO YOU WISH TO BUY? 45

HOW MANY BUSHELS DO YOU WISH TO FEED YOUR PEOPLE? 1000

HOW MANY ACRES DO YOU WISH TO PLANT WITH SEED? 1045
BUT YOU HAVE ONLY 100 PEOPLE TO TEND THE FIELDS!  NOW THEN,
HOW MANY ACRES DO YOU WISH TO PLANT WITH SEED? 500

YOU STARVED 50 PEOPLE IN ONE YEAR!!!
DUE TO THIS EXTREME MISMANAGEMENT YOU HAVE NOT ONLY
BEEN IMPEACHED AND THROWN OUT OF OFFICE BUT YOU HAVE
ALSO BEEN DECLARED NATIONAL FINK!!!!

SO LONG FOR NOW.
```

Evidently, I need some practice.

