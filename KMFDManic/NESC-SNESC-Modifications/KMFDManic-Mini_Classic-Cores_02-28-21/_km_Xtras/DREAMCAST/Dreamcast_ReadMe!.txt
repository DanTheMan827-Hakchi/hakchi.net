First of all!

-You will need BIOS!  Using Master BIOS Module, create a folder named dc (lowercase) inside
libretro/system.  Then, copy dc_flash.bin and dc_boot.bin and naomi_boot.bin into it.  Then,
install like any other HMOD!

-You can add .cdi files as-is, making sure they are NOT compressed.  /bin/reicast

-Large, single file .gdi files can also be added as-is, same deal!  /bin/reicast

-chd files will work, added as-is.  /bin/reicast

-Smaller, 1 KB or less .gdi files are really .cue files.  If they have same checksum
as a previous, smaller .gdi file you've added, it will replace!  There are a few ways
around this!  One, which is safest, and avoids screwing up the .gdi cue contents, is to
compress the smaller .gdi.  Then, make a txt file, and name it the name of the game.  
Then, drag it into the .zip.  Add this .zip as a game, as-is.  Command line it to 
/bin/reicast  Then, go to the end of the command line and change extension to be .gdi
again.

IE: 

MVC2.zip to MVC2.gdi  Then, extract or copy the original MVC2.gdi file into that CLV
Folder.  And, finally, copy the rest of the track files into same CLV, as they are 
dependencies to run the game!  

This happens anytime you attempt to add a game or file that Hakchi reads as identical to a previous one.
It overwrites the former one.  So, by zipping, then throwing a .txt file inside it, it changes the checksum. 

KMFDManic:)


