ScummVM

Welcome to one of the most sought after and requested Cores, ScummVM, which is now fully functional for the Mini NES/SNES!
Myself (KMFDManic), Beylie, and madmonkey happily bring this to you with very high compatibility due to the extra time put 
into generating and putting all but 24 known ScummVM games from the most current set into launcher format, as well as getting 
the Core up and running as optimally as possible! The 24 we still need to make launchers for are at the bottom of this ReadMe!  

For those of you are uninitiated, ScummVM stands for Script Creation Utility for Maniac Mansion Virtual Machine.  It is a truly
amazing subset of Point and Click Adventure and similarly minded games that has developed quite a cult following over the years!
It is a very niche genre and has had more than great success on the most well known games, such as the Monkey Island series...
and, of course Maniac Mansion!  Many have become accustomed to the greatness of Maniac Mansion from its prominence on the original
Nintendo Entertainment System!  

LucasArts is a computer game company founded by George Lucas in 1982. Before becoming a separate entity in 1990, the games were
released under the Lucasfilm Games label.  While building its reputation as a developer of excellent graphic adventure games 
beginning in the late 1980s, the company switched to marketing the Star Wars franchise in the late 1990s. LucasArts was purchased
by Disney in 2012. In April 2013, Disney ceased all development at LucasArts and laid off most of its staff. LucasArts now exists
mostly to license Lucasfilm properties to third party game developers and publishers, however they occasionally serve as a digital 
publisher as well.

LucasArts produced many adventures like the Monkey Island series based on the SPUTM engine, which used the SCUMM scripting language, 
which also gave ScummVM its name.

Maniac Mansion (1987)
Zak McKracken and the Alien Mindbenders (1988)
Indiana Jones and the Last Crusade (1989)
Loom (1990)
Passport to Adventure (1990)
The Secret of Monkey Island (1990)
Monkey Island 2: LeChuck's Revenge (1991)
Indiana Jones and the Fate of Atlantis (1992)
Day of the Tentacle (1993)
Sam & Max Hit the Road (1993)
Full Throttle (1995)
The Dig (1995)
The Curse of Monkey Island (1997)

General Information regarding this Core!

To add games for play on the Mini, use Hakchi to add one of the pertinent launcher files.  Make sure the .scummvm file
is not compressed by Hakchi.  You can disable compress games when adding, or simply right click and decompress after
the fact!  After adding the .scummvm launcher file as a game, navigate to that CLV folder directory, and copy the 
entire contents of whichever game you choose to play into said folder.  Add art, then synch/export, etc:)  Enjoy:)

Launcher wise, there are 3 sets.  One is officially tested, but missing many games!  Two is generated unofficially 
tested ones that cover the missing games from the first set.  Three is generated unofficially, also covering by
platforms!  In testing, the unofficial sets have been quite reliable.  They have not been fully tested, as of yet.
But, you should potentially be able to run all (roughly 435) but 27 games with the unofficial ones!  The officially
tested ones are included as back-up, just in case any of you need to use those instead!  We will work on filling in 
the gaps for the remaining games, as detailed at the bottom of ReadMe!

Some games work with text parsers. For those games you'll need to have a multi-USB adapter and plug in a keyboard.
Refer to http://wiki.scummvm.org/index.php/Datafiles for which files are required for each game.

A couple options that are on PC ScummVM, as well as a couple games, are disabled in this version.  These, for now, 
will not work in our Environment.  They are negligible for the most part, as they do not really affect us so much.
These include Sid music player and the aforementioned couple games.  This will unlikely change anytime soon.

----------------

Game specific files

The following games need the kyra.dat file (location to file goes here ...) copied to their folders to function:
	Lands of Lore: The Throne of Chaos
	Legend of Kyrandia, The
	Legend of Kyrandia, The: Hand of Fate
	Legend of Kyrandia, The: Malcolm's Revenge

The following game needs the lure.dat(location to file goes here ...) copied to it's folder to function:
	Lure of the Temptress

----------------

Additional Files that can be used for certain games.  These are copyrighted and cannot be included, unfortunately.


FMT_FNT.ROM
This file is a dump of the font stored within the FM-Towns bios, it is used for the display of the FM-Towns Kanji text when playing
Japanese FM-Towns games.

MT32_CONTROL.ROM
MT32_PCM.ROM
These two files are dumps of the MT-32 bios, the dumps are used to emulate the MT-32 hardware within ScummVM.

pce.cdbios
This file is a dump of the PC-Engine/TurboGrafx16 System Card, it contains the font data required to display the Kanji text in the
Japanese PC-Engine/TurboGrafx version of Loom.

----------------

How to save games

In preliminary tests, saving via "start" ScummVM menu seemed to worked out quite well.  Other methods, such as RetroArch and Suspend States
may not work or prove to be unreliable.  You can't type a save game name without a keyboard, but the right shoulder button let's you add
the number 5, so that may help to uniquely identify your save games for now.  I delayed this Core Set Release an extra day to ensure you
Guys and Gals would be able to play as many games as possible, with better overall optimization and performance and compatibility, as well 
as had to fix "saves".  We discovered the saves were being deleted upon exiting games and/or shutting down.  I applied a couple adjustments 
and fixes and they should save with both NAND and USB-HOST (hakchi/saves) now:) 
----------------

How to properly exit games

It is best to push "start", then save if you so choose to, then quit.  Avoid quitting from RetroArch or in-game if at all possible.
It may potentially lead to extended waiting period and/or freezing.  But, it quits perfectly if you do it from ScummVM "start" menu.
After you are kicked back to RetroArch, quit normally!

----------------

Games does currently do not have launchers.  In order to generate launchers for these, we need to find the VBA code to
locate the short name files.  Example, Sfinx below is sfinx.  The Big Red Adventure is bra.  Once the short name is 
discovered, the process is much easier, special characters aside!  If any of you figure out any of the missing 24, 
feel free to let me (KMFDManic) know, and we will get the process underway to add them to the Launchers!

Astro Chicken (Floppy DOS)
Christmas Card 1986 (AGI)
Christmas Card 1988 (SCI)
Christmas Card 1990 - The Seasoned Professional (SCI)
Christmas Card 1992 (SCI)
Crazy Nicks Picks King Graham's Board Game Challenge (DOS)
Crazy Nicks Picks Leisure Suit Larrys Casino (DOS)
Crazy Nicks Picks Parlor Games with Laura Bow (DOS)
Crazy Nicks Picks Robin Hoods Game Of Skill And Chance (DOS)
Crazy Nicks Picks Roger Wilcos Spaced Out Game Pack (DOS)
Fun Seeker's Guide to Eastern Madera County (CD, DOS)
Living Books - Arthur's Computer Adventure (CD Windows)
Living Books - Arthur's Reading Race (CD Windows)
Living Books - Cat in the Hat (CD Windows)
Ms Astro Chicken (Floppy DOS)
Open Quest (FanMade - Get's Detected as DOTT)
Playtoons 1 - Uncle Archibald (CD, Windows)
Playtoons 1-4 Combined Install (CD, Windows)
Playtoons 2 - Case of the Counterfeit Collaborator (CD, Windows)
Playtoons 3 - Secret of the Castle (CD, Windows)
Playtoons 4 - The Mandarine Prince (CD, Windows)
Putt-Putt's One-Stop Fun Shop (CD Windows) (In Official Launchers)
Road (Fanmade - Get's Detected as DOTT)
Sfinx v1.1 (DOS, English) (In Official Launchers)
Simon the Sorcerer Puzzle Pack (CD Windows)
The Big Red Adventure (DOS, Multilanguage) (In Official Launchers)

----------------

Thank You!  Enjoy ScummVM!  And, any and all feedback related to this Core, Compatibility, and so on...is hugely welcome!  Like with
Amiga, things can get better with every new Update, potentially!  

Sincerely, KMFDManic!
