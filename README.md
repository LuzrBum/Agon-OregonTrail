# Agon-OregonTrail
Oregon Trail for the Agon Light (TM) 8-bit computer https://www.thebyteattic.com/p/agon.html

How it was made
* Original source http://bbcmicro.co.uk/explore.php?id=2716
* Go to INTRO file and "Download"
* Go to GAME file and "Download"
* Open each file in http://www.bbcbasic.co.uk/bbcsdl/index.html (note you have to select "any file" because they are *.bin)
* In the INTRO file, delete both occurences of "*FX15" (in line 140 and 681)
* Save as "*.BBC"

Copy both files to SD card, insert in Agon Light, powerup.  
In BBC Basic, type:

    LOAD "INTRO.BBC"
    RUN

