---
Name: Xtreme Virtual Ram ALT!
Version: February 24th 2021
Creator: Swingflip|Xorloser
HMOD By: KMFDManic
Category: KMFD Xtreme
---

**This is an ALTernative Version of Xtreme Virtual Ram, modified for Swap 512MB/Zram
**If you have difficulty running the OTHER Xtreme Virtual Ram, use THIS one.  Uninstall the other one, first!
**This Module absolutely requires USB or SD for installation, and creates a 512 MB Swap File on such to minimize game and memory leak crashing!**
**Recommended Ext4 Format for most optimal usage, followed respectively by NTFS, then Fat32!**
This is one of the collaborative efforts that transpired, even with drama going on!  It was theorized by myself and Swingflip that some games and memory leak crashing were the result
of not enough RAM memory to work with!  So, we handled things on two fronts.  One, madmonkey with Zram Crash Inhibitor, which worked directly with the kernel...and, did not require
require USB or SD to install a swap file.  Two, Hakchi Memory Booster, courtesy of Swingflip|xorloser, which added a swap file to USB or SD, and obviously required USB to work!  Both
are great options.  And, they can both actually be used simultaneously, without any conflicts due to the pure beauty of how they both work!  The main caveat to USB/SD method is that 
one generally needs a fairly decent USB Flash Drive for best optimimal use.  A slow flash drive will simply not handle things as well! 

Some benefits to Zram Crash Inhibitor (which installs automatically with all hakchi versions above 3.4.1, in conjunction with Xtreme Virtual Ram, include:

- N64 Games, such as Star Fox 64 will easily get past the 2nd stage+ choke points, where the game ALWAYS runs out of memory!
- N64 Games, generally, have variable amounts of memory leakage.  Some crash in 40 minutes, others in 14 hours.  This increases those times, exponentially!  
- Additionally, you can insta-clear memory leaks on ANY N64 Game by going into RetroArch Settings, Video, Toggle Force-disable sRGB FBO On/Off
- Force-disable sRGB FBO On/Off also works for a number of other Cores!  But, for some Dreamcast Games, you must Toggle twice, or will get graphical glitches!
- Force-disable sRGB FBO On/Off usage on Cores that don't support it, will simply close content on usage of such
- PSP Games, such as God of Wars...that were impossible to run, are actually playable now...especially if you use the exploit to disable audio driver temporarily!
- To disable Audio Driver, without content loaded, go into RetroArch Settings, Audio, Toggle Audio Driver Off.  Exit RetroArch, Reenter, to take effect.  
- Atomiswave/Naomi Games with either/or Dreamcast Core, typically crash...depending on cumulative and overall power draw/usage!  Not anymore:)
- Doom SIGIL, the .wad music sample version, will actually work with the additional memory
- MAME 2003 Xtreme Samples, particularly ones over 80MB, such as Street Fighter II, will no longer crash on memory unload!

### Installation Protocol

1. It is currently set to create and install a 512 MB Virtual Ram Swap File on USB or SD, which must be connected and mounted (USB-HOST)
2. On initial boot up after install sequence, you will see text detailing the process on your TV.
3. `XtremeVirtualRam.swap` file should now exist on your USB or SD!
 
