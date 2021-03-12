***Here are a list of currently supported Command Line Arguments for the Cores in my Set:)*** |

NOTE: With my Core Set, the best ways to run NES/SNES Games are as follow:)

With ANY RetroArch installed 

NES = /bin/fceumm OR /bin/nestopia or /bin/quicknes will point to either NES Core you choose

/bin/nes on NESC will use kachikachi where appropriate, and switch to either fceumm
or nestopia, for unsupported games and/or FDS

SNES = /bin/snes if just one SNES9x Core installed.  Scroll down to the appropriate Core
if more than one SNES Core is installed at a time.  IE: /bin/snes02 and/or /bin/snes05 ,etc

If you have a Canoe Command line, it will run with Default Canoe Emulator.  The Canoe Emulator has
very solid support.  DarkAkuma has an excellent Sfrom Patching Tool, at the following link to help
with troublesome Games:

http://darkakuma.z-net.us/p/sfromtool.html

But, if you'd rather run it with one of the SNES9X Cores, do the following:

IE, Canoe Command Line: 

 /bin/clover-canoe-shvc-wr -rom /usr/share/games/CLV-U-TZGWM/3_Ninjas_Kick_Back_(USA).sfrom --volume 100 -rollback-snapshot-period 600

Changing it to the following will make it run via SNES9x, instead

/bin/snes /usr/share/games/CLV-U-TZGWM/3_Ninjas_Kick_Back_(USA).sfrom --volume 100 -rollback-snapshot-period 600

OR, if more than one SNES9x Installed (point to the 9x Variant you'd like to run it with), As an example:

/bin/snes02 /usr/share/games/CLV-U-TZGWM/3_Ninjas_Kick_Back_(USA).sfrom --volume 100 -rollback-snapshot-period 600

NOW THEN, the Command Line Argument Cheat Sheet:)

drastic
- /bin/drastic <rom> <clover_args> Standard Mode 2.5.3
- /bin/drastic-mic <rom> <clover_args> Accuracy Mode 2.5.4

openbor
- /bin/openbor <rom> <clover_args>

_km_4do
  - /bin/4do <rom> <clover_args>

_km_2048
  - /bin/2048 <rom> <clover_args>

_km_atari800
  -/bin/a52 <rom> <clover_args>
  -/bin/atari800 <rom> <clover_args>

_km_bluemsx
  - /bin/col <rom> <clover_args>
  - /bin/msx <rom> <clover_args>
  - /bin/bluemsx <rom> <clover_args>

_km_bsnes_mercury_performance
  - /bin/bsnes <rom> <clover_args>
  - /bin/bsnes-mercury-performance <rom> <clover_args>

_km_cannonball
  - /bin/cannonball <rom> <clover_args>

_km_caprice32
  - /bin/cap32 <rom> <clover_args>
  - /bin/caprice32 <rom> <clover_args>
  - /bin/cpc <rom> <clover_args>

_km_chailove
  - /bin/chailove <rom> <clover_args>

_km_crocods
  - /bin/crocods <rom> <clover_args>

_km_daphne
  - /bin/daphne <rom> <clover_args>

_km_desmume2015
  - /bin/desmume2015 <rom> <clover_args>

_km_dinothawr
  - /bin/dinothawr <rom> <clover_args>

_km_dosbox
  - /bin/dosbox <rom> <clover_args>

_km_dosbox_svn
  - /bin/dosbox-svn <rom> <clover_args>

_km_eighty-one
- /bin/81 <rom> <clover_args>
- /bin/eighty-one <rom> <clover_args>

_km_emux_chip8
  - /bin/ch8 <rom> <clover_args>
  - /bin/emux-chip8 <rom> <clover_args>

_km_fbalpha2012
  - /bin/fba <rom> <clover_args>
  - /bin/fba2012 <rom> <clover_args>

_km_fbalpha2012_cps1
  - /bin/cps1 <rom> <clover_args>

_km_fbalpha2012_cps2
  - /bin/cps2 <rom> <clover_args>

_km_fbalpha2012_cps3
  - /bin/cps3 <rom> <clover_args>

_km_fbalpha2012_neogeo
  - /bin/neo <rom> <clover_args>

_km_fbalpha2016
  - /bin/fba <rom> <clover_args>
  - /bin/fba2016 <rom> <clover_args>

_km_fbaneo
  - /bin/fba <rom> <clover_args>

  - /bin/fbaneo <rom> <clover_args>

_km_ffmpeg
  - /bin/ffmpeg <rom> <clover_args>

_km_flycast
  - /bin/flycast <rom> <clover_args>


_km_fmsx
  - /bin/msx <rom> <clover_args>
  - /bin/fmsx <rom> <clover_args>

_km_freechaf
  - /bin/freechaf <rom> <clover_args>

_km_freeint
  - /bin/freeintv <rom> <clover_args>
  - /bin/int <rom> <clover_args>

_km_fuse
  - /bin/fuse <rom> <clover_args>
  - /bin/zx <rom> <clover_args>

_km_gambatte
  - /bin/gambatte <rom> <clover_args>
  - /bin/gb <rom> <clover_args>
  - /bin/gbc <rom> <clover_args>
  
_km_gearboy
  - /bin/gearboy <rom> <clover_args>

_km_gearsystem
  -/bin/gearsystem <rom> <clover_args>

_km_genesis_plus_gx
  - /bin/genesis-plus-gx <rom> <clover_args>
  - /bin/gg <rom> <clover_args>
  - /bin/md <rom> <clover_args>
  - /bin/megacd <rom> <clover_args>
  - /bin/segacd <rom> <clover_args>
  - /bin/sg <rom> <clover_args>
  - /bin/sms <rom> <clover_args>

_km_glupen64
  - /bin/glupen <rom> <clover_args>
  - /bin/glupen64 <rom> <clover_args>
  - /bin/n64 <rom> <clover_args>

_km_gme
  - /bin/gme <rom> <clover_args>

_km_gpsp
  - /bin/gpsp <rom> <clover_args>

_km_gw
  - /bin/gw <rom> <clover_args>
  - /bin/mgw <rom> <clover_args>

_km_handy
  - /bin/handy <rom> <clover_args>
  - /bin/lnx <rom> <clover_args>

_km_hatari
  - /bin/hatari <rom> <clover_args>

_km_imageviewer
  - /bin/imageviewer <rom> <clover_args>
  - /bin/img <rom> <clover_args>
  - /bin/jpg <rom> <clover_args>

_km_lutro
  - /bin/lutro <rom> <clover_args>

_km_mame2000
  - /bin/mame2000 <rom> <clover_args>

_km_mame2003_plus_experimental
  - /bin/mame2003-plus <rom> <clover_args>

_km_mame2003_xtreme
  - /bin/mame2003 <rom> <clover_args>

_km_mame2010
  - /bin/mame2010 <rom> <clover_args>

_km_mame2014
  - /bin/mame2014 <rom> <clover_args>

_km_mednafen_gba
  - /bin/mednafen-gba <rom> <clover_args>

_km_mednafen_ngp
  - /bin/mednafen-ngp <rom> <clover_args>
  - /bin/ngc <rom> <clover_args>
  - /bin/ngp <rom> <clover_args>

_km_mednafen_pce_fast
  - /bin/mednafen-pce-fast <rom> <clover_args>
  - /bin/pce <rom> <clover_args>
  - /bin/pcecd <rom> <clover_args>

_km_mednafen_pcfx
  - /bin/mednafen-pcfx <rom> <clover_args>
  - /bin/pcfx <rom> <clover_args>

_km_mednafen_supergrafx
  - /bin/sgfx <rom> <clover_args>

_km_melonds
  - /bin/melonds <rom> <clover_args>

_km_mednafen_gba
  - /bin/mednafen-gba <rom> <clover_args>

_km_mednafen_saturn
  - /bin/mednafen-gba <rom> <clover_args>

_km_mednafen_supergrafx
  - /bin/mednafen-supergrafx <rom> <clover_args>

  - /bin/sgfx <rom> <clover_args>

_km_mednafen_vb
  - /bin/mednafen-vb <rom> <clover_args>
  - /bin/vb <rom> <clover_args>

_km_mednafen_wswan
  - /bin/mednafen-wswan <rom> <clover_args>
  - /bin/ws <rom> <clover_args>
  - /bin/wsc <rom> <clover_args>

_km_mesen
  - /bin/mesen <rom> <clover_args>

_km_mess2016
  - /bin/mess2016 <rom> <clover_args>

_km_meteor
  - /bin/meteor <rom> <clover_args>

_km_mgba
  - /bin/gba <rom> <clover_args>
  - /bin/mgba <rom> <clover_args

_km_mrboom
  - /bin/mrboom <rom> <clover_args>

_km_mupen64plus
  - /bin/mupen <rom> <clover_args>
  - /bin/mupen64plus <rom> <clover_args>
  - /bin/n64 <rom> <clover_args>

_km_mupen64plus-next
  - /bin/mupen-next <rom> <clover_args>
  - /bin/mupen64plus-next <rom> <clover_args>
  - /bin/n64 <rom> <clover_args>

_km_neocd
  - /bin/neocd <rom> <clover_args>
  - /bin/neocd2018 <rom> <clover_args>

_km_np2
  - /bin/nekop2 <rom> <clover_args>
  - /bin/np2 <rom> <clover_args>
  - /bin/pc98 <rom> <clover_args>

_km_np2kai
  - /bin/np2kai <rom> <clover_args>
  - /bin/pc98 <rom> <clover_args>

_km_nxengine
  - /bin/nxengine <rom> <clover_args>

_km_o2em
  - /bin/o2em <rom> <clover_args>

_km_opera
  - /bin/opera <rom> <clover_args>

_km_openbor
  -/bin/openbor <rom> <clover_args>

_km_parallel
  - /bin/n64 <rom> <clover_args>
  - /bin/parallel <rom> <clover_args>
  - /bin/parallel-n64 <rom> <clover_args>

_km_pcsx1_neon
  - /bin/pcsx1 <rom> <clover_args>

_km_pcsx_rearmed_neon
  - /bin/pcsx  <clover_args> (triggers Xtreme NEON Mode Activate!
  - /bin/pcsx-neon  <clover_args> (triggers Xtreme NEON Mode Activate!
  - /bin/pcsx-peops  <clover_args> (triggers Xtreme PEOPS Mode Activate!
  - /bin/pcsx-unai  <clover_args> (triggers Xtreme UNAI Mode Activate!

_km_picodrive
  - /bin/32x <rom> <clover_args>
  - /bin/picodrive <rom> <clover_args>

_km_pocketcdg
  -/bin/cdg <rom> <clover_args> 
  -/bin/mp3 <rom> <clover_args> 
  -/bin/pocketcdg <rom> <clover_args>

_km_pokemini
  - /bin/pokemini <rom> <clover_args>
 
_km_ppsspp_standard
- /bin/ppsspp-standard <rom> <clover_args>

_km_ppsspp_xtreme
- /bin/ppsspp <rom> <clover_args>

_km_prboom
  - /bin/wad <rom> <clover_args>
  - /bin/prboom <rom> <clover_args>

_km_prosystem
  - /bin/a78 <rom> <clover_args>
  - /bin/prosystem <rom> <clover_args>

_km_puae_xtreme
  - /bin/amiga <rom> <clover_args>
  - /bin/uae <rom> <clover_args>
  - /bin/puae-xtreme <rom> <clover_args>

_km_px68k
  -/bin/px68k <rom> <clover_args>
  -/bin/sharp <rom> <clover_args>

_km_quasi88
  -/bin/quasi88 <rom> <clover_args>

_km_quicknes
  - /bin/quicknes <rom> <clover_args>

_km_reicast
  - /bin/reicast <rom> <clover_args> Xtreme Mode Activate

_bin/reminiscence
  - /bin/flashback <rom> <clover_args>
  - /bin/reminiscence <rom> <clover_args>

_km_retroarch_xtreme
  - /bin/fceumm <core> <rom> <clover_args>
  - /bin/fceumm-legacy <core> <rom> <clover_args> For Legacy Saves
  - /bin/ffmpeg <core> <rom> <clover_args> FFMPEG Required
  - /bin/nestopia <core> <rom> <clover_args>
  - /bin/quicknes <core> <rom> <clover_args>
  - /bin/retroarch-clover <core> <rom> <clover_args>
  runs RetroArch with specified core,
  designed for executing from clover shell, 
  so it parses all clover arguments (saves, aspect ratio, etc.)
  - /bin/nes <rom> <clover_args>
  runs "fceumm" core or "nestopia" for FDS games
  - /bin/retroarch-mini [core] [rom] [args]
  runs RetroArch directly, without clover integration
  - /bin/retroarch
  RetroArch binary

_km_sameboy
  - /bin/sameboy <rom> <clover_args>

_km_scummvm
  - /bin/scummvm <rom> <clover_args>

_km_smsplus
  - /bin/smsplus <rom> <clover_args>

_km_snes9x2002
  - /bin/snes <rom> <clover_args>
  - /bin/snes02 <rom> <clover_args>

_km_snes9x2005
  - /bin/snes <rom> <clover_args>
  - /bin/snes05 <rom> <clover_args>

_km_snes9x2005 Plus
  - /bin/snes <rom> <clover_args>
  - /bin/snes05-plus <rom> <clover_args>

_km_snes9x2010
  - /bin/snes <rom> <clover_args>
  - /bin/snes10 <rom> <clover_args>

_km_snes9x2016 Bright
  - /bin/snes <rom> <clover_args>
  - /bin/snes-bright <rom> <clover_args>

_km_snes9x2018
  - /bin/snes <rom> <clover_args>
  - /bin/snes18 <rom> <clover_args>

_km_stella
  - /bin/a26 <rom> <clover_args>
  - /bin/stella <rom> <clover_args>

_km_theodore
  - /bin/theodore <rom> <clover_args

_km_tgbdual
  - /bin/tgbdual <rom> <clover_args>

_km_tyrquake
  - /bin/pak <rom> <clover_args>
  - /bin/tyrquake <rom> <clover_args>

_km_uae4arm
  - /bin/amiga <rom> <clover_args>
  - /bin/uae <rom> <clover_args>
  - /bin/uae4arm <rom> <clover_args>

_km_uae4arm-xtreme
  - /bin/amiga <rom> <clover_args>
  - /bin/uae <rom> <clover_args>
  - /bin/uae4arm <rom> <clover_args>
  - /bin/uae4arm-xtreme <rom> <clover_args>

_km_uzem
  - /bin/uzem <rom> <clover_args>

_km_vba_next
  - /bin/vba-next <rom> <clover_args>

_km_vbam
  - /bin/vbam <rom> <clover_args>

_km_vecx
  - /bin/vec <rom> <clover_args>
  - /bin/vecx <rom> <clover_args>

_km_vice_x64
  - /bin/c64 <rom> <clover_args>
  - /bin/vice-x64 <rom> <clover_args>

_km_virtualjaguar
  - /bin/j64 <rom> <clover_args>
  - /bin/virtualjaguar <rom> <clover_args>

_km_xrick
  -/bin/xrick <rom> <clover_args>

_km_yabause
  - /bin/saturn <rom> <clover_args>
  - /bin/yabause <rom> <clover_args>
