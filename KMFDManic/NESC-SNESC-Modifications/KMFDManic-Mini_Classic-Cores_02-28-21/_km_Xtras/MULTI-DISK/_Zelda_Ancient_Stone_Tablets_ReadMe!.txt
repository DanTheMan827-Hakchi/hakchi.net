Hello, yet again!  This is the absolutely amazing and tremendous method of running all 
4 BS Zelda Ancient Stone Tablet Game Weeks!  Huge personal thanks to Madmonkey and
BsLeNuL and anyone else who has ever dabbled in the trickery of trying to maintain
save integrity between the 4 weeks!  In any case, here is how you do it!

- Install RetroArch 1.7.5 Xtreme, or whichever Xtreme Version you decide to use.
- Add the 4 weeks as separate games, so that they are in their own respective CLV Folders.
- If running the standard roms, not MSU-1 Versions, they should work fine in .Sfrom format,
while compressed.  
- If running the MSU-1 Versions, disable .Sfrom Conversion and Game Compression while adding
within hakchi Options.
- Next, go to the Command Line Perimeters for each of the weeks, from 2 and on, and add
the following Argument:

 --shared-save CLV-FOLDER-NAME-HERE

IE:

/bin/snes18 /var/games/CLV-U-CBDRA/bszelda_mq2.smc.7z

would become:

/bin/snes18 /var/games/CLV-U-CBDRA/bszelda_mq2.smc.7z --shared-save CLV-U-CBDRA

CLV-U-CBDRA is the CLV Folder that I have bszelda_mq1.smc.7z in.  So, week 2 is
now tethered, save wise, to week 1!  Do the same for weeks 3 and 4, tethering those
to week 1!  

NOTE: It is best to use SNES9x2018 AKA SNES9X, for best results, as far as compatibility
for BS-X and MSU-1 games, in general!

Sincerely, KMFDManic!