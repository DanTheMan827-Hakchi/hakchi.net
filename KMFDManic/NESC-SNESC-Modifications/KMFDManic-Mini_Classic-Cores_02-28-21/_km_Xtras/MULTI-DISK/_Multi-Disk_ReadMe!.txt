Personal thanks to Jul Car, BsLeNuL, for their tremendous efforts with testing and helping
me (KMFDManic) better Multi Disk Swapping and Usage for the Mini Classics, as well as any
and all individuals who have previously worked on the coding with Libretro Cores and PC 
Standalone Emulators!

**Cores that currently support .m3u usage, as of this Update, include: BlueMSX, Cap32,
Hatari, Mednafen Saturn, PCSX ReArmed Neon, PCSX1, P-UAE, PX68k, Reicast, ViceX64**

**The included templates can be amended with notepad and used for any of the above listed!

Hello there!  Through the miracle of emulation, many Cores now have the ability to
Multi-Disk Swap!  You can do this a variety of different ways.  But, the .m3u method
is the most optimal to use for many platforms, including the Mini Classics!  I have
included a few templates.  You can amend them using notepad.  The gist is that the
.m3u files are essentially like music playlists...wherein you can point to a set
number of files, which are then utilized via RetroArch and the Cores!  IE:

Nemesis '90 Kai.m3u points to two files;  

Nemesis '90 Kai (Disk 1 of 2).dim
Nemesis '90 Kai (Disk 2 of 2).dim

You would add Nemesis '90 Kai.m3u as a game within Hakchi, making sure it is not
compressed.  Hakchi2 CE, Settings, Disable Compression.  You can, additionally, 
right click on previously compressed items to decompress them.  But, it is always
best to simply add with compression disabled, to avoid any conflicts with formatting,
etc.  After adding the .m3u as a game, via hakchi, simply copy the other 2 pertinent 
files into the same CLV Folder...these being;

Nemesis '90 Kai (Disk 1 of 2).dim
Nemesis '90 Kai (Disk 2 of 2).dim

Doing this will mount those 2 disks, so they can run, by default...when loading the
Sharp X68000 Core (PX68k) with /bin/px68k or /bin/sharp

Bios for this Core, that are needed, are detailed within Xtras/Bios, or in Master BIOS
Module, while viewed within Hakchi!

For PCSX ReArmed NEON, do the same thing.  But, in order to Swap Disks, when you get
prompted to do so, go to RetroArch Settings, Quick Menu, Disk Control, change the Disk
Index from 1 to 2, or whichever disk you are going from and to.  Depending on the game, 
you may need to click Disk Cycle Tray Status with the A Button to eject the disk.  Then, 
you can change the Disk Index.  Then, reclick Disk Cycle Tray Status to reinsert the
disk.  And, finally, "resume" the game for it to switch over.

Additionally, depending on platform, there is a little bug that some may run into.  This 
will be looked into more in the future, as far as cleaning things up.  But, once you swap
disks, make an in-game memory card save.  This will allow suspend states to work for
getting back to disk 2, etc!  Without making an in-game save, you may end up running
into graphical glitches or games freezing, etc.

IE: for Metal Gear Solid:

Metal Gear Solid .m3u pointing to Disk 1 and 2 .cues, pointing to Disk 1 and 2 .bins.  Like
so!

Metal_Gear_Solid.m3u contains:

Metal_Gear_Solid_CD1.cue
Metal_Gear_Solid_CD2.cue

Each of those cues contain, respectively:

Metal_Gear_Solid_CD1.bin for CD1.cue

and

Metal_Gear_Solid_CD2.bin for CD2.cue

So, again:

- RetroArch Settings, Quick Menu, Disk Index (possibly need Disk Cycle Tray Status),
Resume, In-Game Save, Suspend State, Gold!

As things progress, I will update this ReadMe! 

Sincerely, KMFDManic!

As always, feel free to ask any questions.  And, I will be glad to help out!



