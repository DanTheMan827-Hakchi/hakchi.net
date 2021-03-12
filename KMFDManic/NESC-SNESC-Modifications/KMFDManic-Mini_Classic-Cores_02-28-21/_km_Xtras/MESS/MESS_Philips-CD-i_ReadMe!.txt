You can now run Philips CD-i with MESS!  Follow these steps:)

1.  Have latest Injector for AutoBleem/BleemSync installed if on PSC; MESS Dependencies and MESS Core HMODs installed if on NESC/SNESC 

2.  Create a cdimono1 folder wherever you plan on running the CD-i games from, if on PSC

3.  Place cdimono1.zip CD-i BIOS within said folder

4.  Copy and paste whichever CD-i game you'd like to run, also into cdimono1 folder

5.  From CDI_blank.zip, copy the _DUMMY file/s you want for any given game.  These are what will "load" and point to your hard files.
IE: zeldgamu.zip would be selected with MESS Core, in order to load the US version of Zelda: Wand of Gamelon  You would need to have
the Zelda: Wand of Gamelon bin+cue or chd within cdimono1 directory

6.  If on NESC/SNESC, things are slightly trickier.  You can run things easily from _DUMMY folder method, obviously!  But, in order
to run from the Main UI, you would need to add, as an example, zeldagamu.zip as a game, as is.  Then, navigate to that CLV folder, 
then create cdimono1 folder, and drag zeldagamu.zip inside of it.  Then, copy the cdimono1.zip BIOS and game you'd like to run into
the same folder.  Example command line when done would be:  

/bin/mess /var/games/CLV-Z-NNOEA/cdimono1/zeldagamu.zip

You would need to manually change it to be like this (CLV may vary), then close Hakchi, Reopen, then export.

NOTE: MOST of the _DUMMY files are empty, so you will get an unhandled exception error with hakchi when accessing them.
To get around this, simply create a text file, using notepad, that matches the name of the DUMMY.zip.  For example, 
burncycl.zip create burncycl.txt and drag it into the burncycl.zip  This is also a workaround I devised awhile back
to easily bypass Hakchi's checksum check perimeter.  This is quite helpful in the cases where checksums match.  You 
can, of course, add these, as is.  And, if the unhandled exception error pops up, simply click continue!

If any of you have issues running these, feel free to ask, and I will do my best to help you along!


Sincerely, KMFDManic! 