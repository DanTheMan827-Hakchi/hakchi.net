UPDATE 5-12-18

More Aggressive Games will be accounted for within the context of the Specific Games Folder!!!
Feedback and communication from any and all of you who are fellow Amiga Fans would be 
absolutely tremendously beneficial to getting many more games to run better!

Personal Thanks to qclart and mnx78 for finding some better settings for AGA Games!

You will find many AGA Games have huge performance issues with sound+frame rate.  You can use this template
as an example to help with some of them, such as Agony and Aladdin!  IE:

chipset=ocs
cpu_type=68000
cpu_speed=10
finegrain_cpu_speed=5120
immediate_blits=true
gfx_framerate=2
collision_level=none

For OCS games changing to the faster 68020 (A1200 processor) helps with performance issues in some cases e.g. Zeewolf 
(Thanks to u/mnx78 for this tip!)

Each of these Templates specifically caters to a specialized set-up on your Mini NES/SNES

I can easily add more, if any of you have any situational set-up you'd like them done for!

I may also look into a batch method!

You can use Notepad++ to amend these, case by case, depending on whether you are using:

NOTE: MUST Be named _DUMMY, not _Dummy  In previous Updates, since case sensitivity was not a
factor, I had it as _Dummy.  So, if you currently have a _DUMMY folder, rename it to _DUMMY
Also, location of _DUMMY folder may need amended within _Dummy Folder Templates, due to current
changes to hakchi2 CE Folder Structuring, ie: hakchi/games/snes_eur/CLV-Folders Here  So, keep 
this in mind! 

Hilly also suggested an excellent, alternative tip for those who are more accustomed to this whole process! 

Create a folder on your USB drive outside of Hakchi e.g. USB: AMIGA and use it to store all your Amiga BIOS and WHDLoad games.
There will then be a single fixed path to all your files. If you update your UAE templates to point to this fixed path then all
you're have to do in terms of UAE configuration when adding a game is to add the name of your game's HDF file. When you create your
game HDF file you can write it direct to this location so that when you add your UAE file to Hakchi you're all set and there's no
further configuration or copying files required!  (It is still suggested to retain the integrity of the BIOS files being in system)

Extra Notes

_Dummy Folder on NAND (Use _Dummy Folder HMOD in my set, and create AMIGA folder inside _Dummy
Then, amend the template file to match the game name, internally.

_Dummy Folder on USB (Create hakchi/games/_Dummy/AMIGA
Then, amend the template file to match the game name, internally.

Non-USB HOST (Amend UAE file, with game name, then add via Hakchi, then amend CLV-FOLDER into UAE.
Or, use Archive Method that I go over in my two Amiga Video Tutorials:)

USB-HOST (Same as Non-USB-HOST)

Linked Export (Create in root of Flash Drive, Hakchi2CE.
Then, simply modify game name and CLV-FOLDER names, accordingly, as per above:)

And, so on!

Feel free to ask any questions if any of you need any help!

Sincerely, KMFDManic!!!  Long live Amiga!


