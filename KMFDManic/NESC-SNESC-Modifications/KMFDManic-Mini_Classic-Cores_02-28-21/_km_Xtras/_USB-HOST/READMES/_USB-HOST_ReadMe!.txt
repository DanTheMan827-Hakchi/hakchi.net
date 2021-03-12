NOTE: This is mainly for Archive Purposes, at this point:)  Many things have
changed, USB-HOST wise!  So, take anything you read with a grain of salt!

**********Read everything multiple times before starting**********

***Welcome to Expandable Storage USB Modification (AKA USB-HOST) ReadMe, courtesy
of the hard work and perseverance of none other than madmonkey, the 
original hakchi originator!  Through his efforts, as well as cluster's and 
honeylabs, and countless others, we have come a long way!!!*** 
 
This ReadMe was put together by madmonkey & KMFDManic & AceVanquish, to help 
with the generally non user-friendly nature of this mod. 
 
Prototype was tested by madmonkey, AceVanguish, DanTheMan827, skogaby, Melthris, 
Liriel, and myself. If you have issues with Official Release, feel free to try 
with the bundled Prototype.
 
You will now have the ability to run practically ANY game, no matter its size, 
in full form, music+videos!, as long as it is supported!  Not all are tested.
But, for PS1, you should be able to run Diablo, SOTN, FF7, Road Rash, etc.;
For PicoDrive, 32X CD; SNES 9X, MSU-1 Games!  This also applies to Sega-CD, 3DO, 
Sega Saturn, etc.  The sky is the limit!  Only your imagination, Storage Memory, 
and Inode Index Max, limit you!  View the bundled jpg example of this truly
amazing Modification in the flesh! 
 

***Now for the Disclaimers and other Important Notes*** 

-First and foremost, follow the instructions carefully.  This will not immediately work
for everyone!  Software and hardware issues aside, I tested with 3 different USB Port
Devices, before finding 1 that worked. Be patient!  And, hopefully all will go well!
Your conflict will likely be either hardware based or user-end based:)  
 
-Pay attention to the bundled jpgs.  These are examples of recommended wiring and 
device type.  The switch on whichever device should be permanently in OTG position, 
and no data lines to 'usb male'(power source).

-Please do not inundate Github with "Issues" on this method.  It is primarily 
meant for advanced users, due to its non user-friendly nature. 
If you do have issues, please use absolute discretion before posting an "issue".  
Otherwise, it may be just ignored and closed. 
 
-Back-Up your files before following-through on this and any other 
modifications, as is always recommended! 
 
-Once you flash, hakchi2 will not work, except for installing hmods. (retroarch 
and/or other system emulator cores).  It is recommended to 
install the HMODS you plan to use before flashing for USB Storage, for best 
results. 
 
-If things do not work out successfully, simply uninstall via Hakchi2, using 
original Kernel in hakchi2/dump folder, and try again, if you wish:) 
 
-It's advised not to use pc/tv USB inputs for power - more often than not, there 
will be not enough power. Chargers with 1A or more work best. 
 
-Both NTFS/FAT32 Work.  But, it would be advisable to use ext2/3, if at all possible.
Priority wise, first would be ext2/3, then FAT32, then NTFS (least recommended).
 
-Folders should work. 
 
-Games should go to /hakchi/games  And, they work with both NESC/SNESC. 
 
-If you mkdir /hakchi/saves on external storage, it will save there.  It may be 
slow, though. 
 
-You can load hsqs files as roms from external storage. 
 
-Paths in desktop files should point to /var/games  Paths are now /var/games 
instead of /usr/share/games and /var/saves instead of 
/var/lib/clover/profiles/0. Old paths would still work.  But, they break once 
you boot snes to nes or vice-versa. These will work in both modes. 
 
-Font Issues - font issues, these are only on nes and there are 2 fixes.  Either 
mount usb read-write, so that code that's already there can put 
relevant font files on there.  Or put fixed font files in each directory 
beforehand. That's assuming you have cluster's fontfix hmod installed. 
 
-Despite using an OTG, this is not true OTG, It's host-only mode. OTG is 
switching between host/device mode. 
 
-Untested, fully.  But, USB Controllers, keyboards, etc, should work!  This can 
potentially be amazing for Commodore 64, Dosbox, CPC Amstrad, 
ZX Spectrum, and so on! 
 
-some hmods might conflict with this setup. particularly clovershell, dual-boot
fixes and 'more space' mods. uninstall those. if still no luck, try this:

create file: mod/hakchi/transfer/earlybird
type:
umountSquash
rm -rf "$installpath"

make sure it ends on empty line
rebuild kernel.img
memboot
then install fontfix and ra modules

-If using hakchi2 to install hmods, they should update scripts in hakchi2 as well, ie
rm -rf hakchi2/mods/mod_hakchi/*
rsync -ac "hakchi/mod/" "hakchi2/mods/mod_hakchi/"

Otherwise, it probably won't even boot after hakchi2. you can also do rebuild+memboot
from hakchi afterwards, but this takes more time.

-This script is what was used to fix paths from what other tools put in there:

#!/bin/sh

find -type f -name "*.desktop" | xargs -n1 sed -i 's#/usr/share/games/nes/kachikachi#/var/games#'
find -type f -name "*.desktop" | xargs -n1 sed -i 's#/usr/share/games#/var/games#'
find -type f -name "*.desktop" | xargs -n1 sed -i 's#/var/lib/clover/profiles/0#/var/saves#'

***Now For the Instructions*** 
 
1.  Connect the NESC/SNESC directly to your pc with micro USB the same way you 
would when using Hakchi2. 
 
2.  Supply your own kernel in dump/kernel.img; snes kernel if you're going to 
flash snes, and nes kernel if you're going to flash nes. 
 
3.  press in order: 
    dump kernel.img 
    unpack kernel.img 
    flash kernel 
    rebuild kernel.img 
    memboot 
 
4.  Create /hakchi/games directory on Storage Device, and populate with CLV-* folders just 
how you would /usr/share/games[/nes/kachikachi]  You can still 
use hakchi2 to create the CLV-* folders and artwork thumbnails.  After creating 
them in hakchi2, copy/paste the whole CLV-* folder(s) from 
hakchi2/games_snes to hakchi/games folder on your USB drive. 
 
5.  At this point you can switch to your micro USB OTG. Connect power to the 
micro USB female end. Plug in the micro USB male end to the 
NESC/SNESC. 
 
6.  Insert your prepared USB drive into one of the USB A female ends. 
 
 
***If you are still reading, here is the link to Expandable Memory USB Storage 
Modification, AKA USB-HOST:) 
 
https://github.com/madmonkey1907/hakchi/releases 
 
Note, this ReadMe may change, and be updated, accordingly.
 
Sincerely, 
 
  KMFDManic 
 
