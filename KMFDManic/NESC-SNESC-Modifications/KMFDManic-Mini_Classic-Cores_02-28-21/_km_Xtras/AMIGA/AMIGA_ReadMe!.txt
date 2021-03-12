Personal thanks to  qclart, madmonkey, , mnx78, and /\ + 0 / 9 (darn unicode:) for all of their efforts with helping get this Core off the ground!!!

qclart's Exceptional Typewritten Tutorial

https://www.reddit.com/r/miniSNESmods/comments/8dbqv7/guide_playing_amiga_games_on_the_snes_classic/

Brief Notes:)

KICKSTART BIOS: 

(These can be legitimately be purchased for $30 USD at http://www.amigaforever.com/ PC and 
$3 USD on Mobile Phone (Great tip, DrSPHorn!)

BIOS	                                        Re-name it to.....	What's it for?
WHDLoad.hdf                                                             Loading .hdf games     
Kickstart v3.1 rev 40.63 A500-A600-A2000	kick31.rom	        Running WHDLoad games
Kickstart v1.3 rev 34.5 A500-A1000-A2000-CDTV	kick34005.A500	        Original Chip Set (OCS) games
Kickstart v2.04 rev 37.175 A500+	        kick37175.A500          Enhanced Chip Set (ECS) games
Kickstart v3.1 Rev. 40.063 a600                 kick40063.A600          Enhanced Chip Set (ECS) games
Kickstart v3.1 rev 40.68 A1200	                kick40068.A1200	        Advanced Graphics Architecture (AGA) games
Kickstart v1.2 rev 33.180 A500-A2000	        kick33180.A500	        Some older OCS games

kick31.rom goes into Master BIOS Module/System Folder, and is installed like any other HMOD

The other 4 are embedded into WHDLoad.hdf, via ADFOpus1_2.exe, into devs/kickstarts folder.  And, the
resulting WHDLoad.hdf also goes into Master BIOS Module/System Folder (along with kick31.rom (Install
BIOS Module as HMOD, afterwards:)

ADFOpus1_2.exe can also be used to convert Amiga Roms into Hard Drive Images for use with P-UAE!

ie: 

ShadowOfTheBeast.Slave must be changed to game.slave before converting to .hdf!

Then, that and the rest of the files can be dragged and dropped, accordingly, into NEW, properly sized, .hdf file!

NOTE: Always use source slave directory, when adding files to .hdf files, or some games may not load!

Use Template Files that qclart, mnx78, ^ + 0 / 9, and myself modified, to appropriately point to the paths on NESC/SNESC!

You can amend these with Notepad++, on a case by case basis:)

Add uae template configuration file as a Game

IE: /bin/puae /var/games/CLV-Z-XBWZI/sotb.uae is templateOCS.uae, renamed to match the game!

You can use both /bin/puae and /bin/uae (if on 4-20-18 Core and on)

Then, right click on specific uae file, and edit with notepad++, preferably, so paths match location

IE:

hardfile=read-write,32,1,2,512,<PATH TO YOUR GAME.hdf>

would potentially be changed to:

hardfile=read-write,32,1,2,512,/var/games/CLV-Z-XBWZI/sotb.hdf

You would need to copy sotb.hdf into CLV-Z-XBWZI Folder, then synch/export/manually transfer:)

Always Close/Re-Open Hakchi after making adding any new Games and/or making desktop file changes!  

Sincerely, KMFDManic!

P.S.  The Written Tutorial, my Video Tutorial, this ReadMe!, will all be Updated, as need be, based on user feedback:)  
Enjoy this amazing Core!  This has been the most requested Core, aside from Dreamcast, Nintendo DS, PSP!