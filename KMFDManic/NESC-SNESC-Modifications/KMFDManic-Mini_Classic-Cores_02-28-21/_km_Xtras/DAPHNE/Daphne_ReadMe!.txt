Daphne is a fantastic Laserdisc Game Emulator! (No sound support for the time being!)

Structure to follow when adding games:

Example!

/bin/daphne /var/games/CLV-Z-WIMKU/Daphne/roms/roadblaster.zip

-Added roadblaster.zip as a game, as is.

- Command Line /bin/daphne

-Navigated to CLV Folder, and created Daphne/roms and dragged
roadblaster.zip inside it.

-Amended Command line to above example (adding Daphne/roms )

-Create framefile folder inside Daphne, and copy pertinent Daphne
Game/Music/Video Files into it.  

IE:

Daphne/framefile/ contains roadblaster.dat, roadblaster.m2v, 
roadblaster.ogg, and roadblaster.txt

roadblaster.txt points to location of files!

.
1 roadblaster.m2v

The . means (Files contained within THIS directory!)

If using _DUMMY Folder method, load the rom from within
Daphne/roms, while retaining rest of the above outlined
structure!

Enjoy the Core!!!

KMFDManic:)