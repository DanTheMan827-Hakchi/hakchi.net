NOTE:) samples can be installed via km_mame_custom_samples.hmod

Thanks to the hard work and dedication and patience of gpstar!,
we now have support in MAME 2003 Xtreme for the ability to run a very special Custom Soundtrack with
NBA Jam, specifically, most optimal for use with rom set nbajam.zip
gpstar has done an exceptional job!

Sincerely, KMFDManic!!!  (May we only get more of these incredible Custom OST Mods in the future, for MAME 2003!:)

There are 2 rom sets that work, Rev 3 and Rev2 of nbajam.

Rev3 is: nbajam.zip
Rev2 is: nbajamr2.zip

The arcade version does not have music for the intro, so I had to do some workarounds to get the intro music from the segacd version to 
play during the demo intro titles. Rev3 and Rev2 worked differently on the byte offsets, so it was a bit more tricky.

nbajam.zip is the music file set for Rev3, nbajamr2.zip is for Rev2. Both can use the same sample set.  You can just rename nbajam.zip
samples to whichever rom set you are using it with, be it nbajam.zip or nbajamr2.zip

The music files are as follows:

main-theme-01.wav
main-theme-02.wav
team-select-01.wav
team-select-02.wav
ingame-01.wav
ingame-02.wav
ingame-03.wav
ingame-04.wav
intermission-01.wav
intermission-02.wav
halftime-01.wav
halftime-02.wav
theme-end-01.wav
theme-end-02.wav

Most are self explanatory. Just like Final Fight and Mortal Kombat, -01 is the left channel, -02 is the right channel. For ingame-03,
and ingame-04, 03 is the left channel and 04 is the right channel. Those are played in the 2nd and 4th quarters. Ingame-01 and 02 are 
for the first and 3rd quarters and overtime.

theme-end-01 is not from the segacd, it's from a source i found online, it's a remix of the team-select theme. The arcade version during
the credit sequence (after finishing a full game) plays the team select music. The rest of the music is from the sega cd ost.

Also one thing, in my testing, it seems the snes mini can not handle samples of a totalsize of 160mb or greater (when unzipped). It seems
to run out of memory at that point.

I also blocked out two of the original voices "Welcome to NBA Jam" and "NBA JAM Halftime Report,  Altitude with a attitude" as the original
arcade samples are low quality, and instead I mixed the segacd ost voice samples from the soundtrack into the sample music tracks for clearer
voice for those 2 voice samples. 
