MESS is a Multi-Emulator Super System that is Advanced Level and generally requires
a bit of previous Emulation Experience to truly be able to get into!  It is a nice
thing to try out and have fun with, for sure!  I will continually do what I can to
make it more accessible to everyone!  

For the Playstation Classic, due to its better specs, MESS Emulation is handled a 
great deal better than on the Mini NES/SNES!  So, that is the best recommendation
as far as MESS.

This time around, thanks to the great help and collaboration of Greenchili, Adam
Computer now works!  I (KMFDManic) will get together some Video Tutorials on this,
for those who are less initiated!  The files you will need, dependency wise, are
in:

_km_NESC-SNESC/km_mess2016_dependencies.hmod for SNESC/NESC  BIOS are required
for many of the Emulators that run, including Adam.  Ones like NES do not!

For PSC, the dependencies are now included in the Injector Installers, within
retroarch/system  You will need to, of course, add BIOS!  The bios file needs
to be directly outside of each folder.  

Example Directory structure..

MESS
  adam.zip ( adam BIOS ROMS )

MESS\adam ( has to be named adam)
  your games.  Games must be zipped and use the same exact <software name> AND CRC as listed in the adam_flop.xml file.

MESS\adam\mame\cfg\
  adam.cfg
  default.cfg

make sure you copy the adam.cfg and default.cfg into the "mame\cfg" folder where your games are at or the keyboard mappings
Greenchili created wont work.

Controls.. Have been mapped to best accommodate the Keypad, Keyboard and function keys which are used by a good many games.

KP = Keypad, KB = Keyboard, F is function key.

L1 to toggle keyboard mode, enable GUI.
L2 mess GUI.
R2 show framerate.

dpad = Joystick & Arrow Keys KB

A/Circle   = Button 1
B/X        = Button 2
X/triangle = KP 0, KB 0

Left analog up    = KP 1, KB 1, F1
Left analog left  = KP 2, KB 2, F2
Left analog right = KP 3, KB 3, F3
Left analog down  = KP 4, KB 4, F4

Right analog up    = KP 5, KB 5, F5
Right analog left  = KP 6, KB 6, F6
Right analog right = KP 7, KB 7
Right analog down  = KP 8, KB 8

Y/Square = KP 9, KB 9, F9

Select = *
Start  = # , KB Return

Sincerely, KMFDManic!
 

