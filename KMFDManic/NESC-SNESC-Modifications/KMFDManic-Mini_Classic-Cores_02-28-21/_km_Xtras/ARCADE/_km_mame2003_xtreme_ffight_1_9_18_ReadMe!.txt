NOTE:) samples can be installed via km_mame_custom_samples.hmod

Thanks to the hard work and dedication and patience of big blue frontend and gpstar!,
we now have support in MAME 2003 Xtreme for the ability to run the Sega CD Soundtrack along
with Final Fight Arcade Version!  These were originally introduced in a modified
version of MAME 0.185 by big blue frontend, and backported into MAME 2003 by
gpstar!  Both have done an exceptional job!

Sincerely, KMFDManic!!!  (One can only hope for more of these truly astounding Custom OST Mods for MAME 2003, in the future!:)

gpstar Notes:)

The Soundtrack can be run a few different ways!  These include 8bit mono, 
8 bit mono-stereo non-usb host, and 8bit mono-stereo mix.  Specific notes 
about each of these are contained at the bottom of this ReadMe!

The files need to be within either MAME_Samples.hmod, within mame2003/samples
OR, via ftp, within /etc/libretro/system/mame2003/samples

They must be contained inside a folder named ffight or a zip named ffight
But, if in folder format, it will take up much more space!  So, it is
best recommended to use .zip format.

You can run without ALL of them.  But, if you decide to remove any...due to
space limitations, remove from 26 and go backwards.  if track02-01.wav and 
track02-02.wav are missing, the system will fall back and default to the 
original music from the game!  Keep that in mind. If installing samples via
Hakchi2, invalid kernel size may trigger if too big!  So, you will have to
either cut some of the files out, or use FTP to transfer them.  USB-HOST
will not have any issue running the Full Soundtrack, since there is no
kernel size limit, other than internal NAND Flash Memory Limit, in installing 
HMODS using hakchi/transfer folder!

The proper file names for the Soundtrack need to be, for each of them:

--8bit mono=

track02-01.wav
track03-01.wav
track04-01.wav
track05-01.wav
track06-01.wav
track07-01.wav
track08-01.wav
track09-01.wav
track10-01.wav
track11-01.wav
track12-01.wav
track13-01.wav
track14-01.wav
track15-01.wav
track16-01.wav
track17-01.wav
track18-01.wav
track19-01.wav
track20-01.wav
track21-01.wav
track22-01.wav
track23-01.wav
track24-01.wav
track25-01.wav
track26-01.wav

8 bit mono-stereo non-usb host

track02-01.wav
track02-02.wav
track03-01.wav
track03-02.wav
track04-01.wav
track04-02.wav
track05-01.wav
track05-02.wav
track06-01.wav
track06-02.wav
track07-01.wav
track07-02.wav
track08-01.wav
track08-02.wav
track09-01.wav
track09-02.wav
track10-01.wav
track10-02.wav
track11-01.wav
track11-02.wav
track12-01.wav
track12-02.wav
track13-01.wav
track13-02.wav
track14-01.wav
track14-02.wav
track15-01.wav
track15-02.wav
track16-01.wav
track16-02.wav
track17-01.wav
track17-02.wav
track18-01.wav
track18-02.wav
track19-01.wav
track19-02.wav
track20-01.wav
track20-02.wav
track21-01.wav
track21-02.wav
track22-01.wav
track22-02.wav
track25-01.wav
track25-02.wav
track26-01.wav
track26-02.wav

8big mono-stereo mix

track02-01.wav
track02-02.wav
track03-01.wav
track03-02.wav
track04-01.wav
track04-02.wav
track05-01.wav
track05-02.wav
track06-01.wav
track06-02.wav
track07-01.wav
track07-02.wav
track08-01.wav
track08-02.wav
track09-01.wav
track09-02.wav
track10-01.wav
track10-02.wav
track11-01.wav
track11-02.wav
track12-01.wav
track12-02.wav
track13-01.wav
track13-02.wav
track14-01.wav
track14-02.wav
track15-01.wav
track15-02.wav
track16-01.wav
track16-02.wav
track17-01.wav
track17-02.wav
track18-01.wav
track18-02.wav
track19-01.wav
track19-02.wav
track20-01.wav
track20-02.wav
track21-01.wav
track21-02.wav
track22-01.wav
track22-02.wav
track23-01.wav
track23-02.wav
track24-01.wav
track24-02.wav
track25-01.wav
track25-02.wav
track26-01.wav
track26-02.wav


Additional Notes from gpstar!

I did up 3 different sound sample files. 8bit mono, 8bit mono/stereo mix
and 8bit mono/stereo mix non-usb mod. The non usb mod I removed 2 tracks
of audio so it can fit on my snes mini better without usb host. (tracks 24
and 25, which are not used at all so they arent needed)

The audio formats that mame2003 will handle is as follows:
8bit mono wav
16 bit mono wav

To recreate a stereo effect of the original music, i extracted the sega cd 
music, opened up each track, split the stereo channels separate, and convert
each channel to a mono track and save them out.  If you take a look inside
the ffight.zip samples you will see track02-01.wav and track02-02.wav. 
01 is the left channel converted to mono, and track02-02.wav is the right 
channel converted to mono. The updated cps code will play back both files 
together, and mixes the track02-01.wav into the left speaker and 
track02-02.wav into the right speaker, thus simulating the original 
stereo track.

I also built in hooks, so if only one of the 2 channels play, it will 
default the playing one into both speakers, it'll be a mono effect but
it'll still work, and is another option for people to cut down on file
size.  So for example if in the ffight.zip, track02-02.wav is missing,
the cps system will play track02-01 into both speakers. Or if 
track02-01.wav is missing, it will play track02-02.wav into both speakers.
