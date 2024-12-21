# Emulator List

This is just simply a list of systems, emulators available, rom formats, and bios required. 

* This list is extremely incomplete
* Libretro = RetroArch
* This doesn't take into account if the emulator works on the Retroid Pocket 5
* Some BIOS are optional 
* Some BIOS for RetroArch need to be in folders
* RetroArch BIOS need to be place in the `RetroArch\system` folder

## 3DO Interactive Multiplayer
Category|Information
:-------|:----------
Libretro Cores| Opera
Format|.iso, .chd, .bin/.cue
ES-DE Folder|3do
Required BIOS| panafz1.bin, panafz10.bin, panafz10-norsa.bin, panafz10e-anvil.bin, panafz10e-anvil-norsa.bin, panafz1j.bin, panafz1j-norsa.bin, goldstar.bin, sanyotry.bin, 3do_arcade_saot.bin

## Amstrad CPC
Category|Information
:-------|:----------
Libretro Cores| Caprice32 
Standalone Emulators| andcpc, CPCDroid, Droid-CPC
Format|.cpc, .dsk, .zip, .7z|
ES-DE Folder|amstradcpc

## Apple II
Category|Information
:-------|:----------
Libretro Cores| MESS
Standalone Emulators| Mame4Droid2024
Format|.cmd, .zip
ES-DE Folder|apple2
Require BIOS|apple2.zip, apple2p.zip, apple2e.zip, apple2ee.zip, apple2c.zip, apple2cp.zip, apple2gs.zip

## Arcade
Category|Information
:-------|:----------
Libretro Cores| Final Burn Neo, Final Burn Alpha, Flycast, MAME-current, MAME 2000, MAME 2003 Midway, MAME 2003, MAME 2010
Standalone|MAME4droid, MAME4droid 2024
Format|.zip, .7z
ES-DE Folder (Final Burn Neo)|fbneo
ES-DE Folder (MAME)|mame
BIOS Folder Name (Final Burn)|`RetroArch\system\fbneo\`, `RetroArch\system\fbneo\cheats\`, `RetroArch\system\fbneo\samples\`
BIOS Folder Name (MAME)|`RetroArch\system\mame\bios\`, `RetroArch\system\mame2003-plus\samples\`
Required BIOS|bubsys.zip, cchip.zip, channelf.zip, coleco.zip, decocass.zip, fdsbios.zip, isgsm.zip, midssio.zip, msx.zip, namcoc69.zip, namcoc70.zip, namcoc75.zip, neocdz.zip, neogeo.zip, ngp.zip, nmk004.zip, pgm.zip, skns.zip, spec128.zip, spec128k.zip, spec48k.zip, spectrum.zip, ym2608.zip

## Arduboy
Category|Information
:-------|:----------
Libretro Cores| arduous, ardens
Format|.hex|
ES-DE Folder|arduboy

## Atari 2600
Category|Information
:-------|:----------
Libretro Cores| Stella, Stella 2014
Format|.a26, .bin, .zip, .7z|
ES-DE Folder|atari2600

## Atari 5200
Category|Information
:-------|:----------
Libretro Cores| a5200, Atari800
Format|.a52, .bin, .zip, .7z
ES-DE Folder|atari5200
Required BIOS| 5200.rom, ATARIBAS.ROM

## Atari 7800
Category|Information
:-------|:----------
Libretro Cores| ProSystem
Format|.a78, .zip
ES-DE Folder|atari7800
Required BIOS| 7800 BIOS (U).rom

## Atari Jaguar
Category|Information
:-------|:----------
Libretro Cores| Virtual Jaguar
Standalone| IrataJaguar, MAME4droid 2024
Format|.j64, .jag, .rom, .abs, .cof, .bin, .prg|
ES-DE Folder|atarijaguar

## Atari Lynx
Category|Information
:-------|:----------
Libretro Cores| Beetle Lynx, Handy
Standalone| Lynx.emu
Format|.7z, .lnx, .zip
ES-DE Folder|atarilynx
Required BIOS| lynxboot.img

## Atari ST/STE/TT/Falcon
Category|Information
:-------|:----------
Libretro Cores| Hatari
Format|.st, .msa, .stx, .dim, .ipf, .zip
ES-DE Folder|atarist
Required BIOS| tos.img

## Bandai WonderSwan
Category|Information
:-------|:----------
Libretro Cores| Beetle Cygne
Format|.ws, .pc2, .zip, .7z|
ES-DE Folder|wonderswan

## Bandai WonderSwan Color
Category|Information
:-------|:----------
Libretro Cores| Beetle Cygne
Format|.ws2, .pc2, .zip, .7z|
ES-DE Folder|wonderswancolor

## Chai Love
Category|Information
:-------|:----------
Libretro Cores| Chai Love
Format|.chai, .chailove|
ES-DE Folder|chailove

## CHIP-8/S-CHIP/XO-CHIP
Category|Information
:-------|:----------
Libretro Cores| JAXE
Format|.ch8, .sc8, .xo8|

## Coleco Vision
Category|Information
:-------|:----------
Libretro Cores| blueMSX, Gearcoleco
Standalone| MSX.emu, ColEm
Format|.rom, .ri, .mx1, .mx2, .col, .dsk, .cas, .sg, .sc, .m3u, .zip, .7z
ES-DE Folder|colecovision
BIOS Folder Name|`RetroArch\system\Databases\*`, `RetroArch\system\Machines\*`
Required BIOS| coleco.rom, [blueMSX](http://bluemsx.msxblue.com/download.html)

## Commodore Amiga
Category|Information
:-------|:----------
Libretro Cores| PUAE 2021, PUAE
Format|.adf, .hdf, .lha, .zip
ES-DE Folder|amiga
Required BIOS| kick33180.A500, kick34005.A500, kick40068.A1200

## Commodore Amiga CD32
Category|Information
:-------|:----------
Libretro Cores| PUAE 2021, PUAE
Format|.cue, .ccd, .chd, .lha, .nrg, .mds, .iso.
ES-DE Folder|amigacd32
Required BIOS| kick40060.CD32, kick40060.CD32.ext

## Commodore C128
Category|Information
:-------|:----------
Libretro Cores| VICE x128
Format|.d64, .d71, .d80, .d81, .d82, .g64, .g41, .x64, .t64, .tap, .prg, .p00, .crt, .bin, .zip, .gz, .d6z, .d7z, .d8z, .g6z, .g4z, .x6z, .cmd, .m3u, .vsf, .nib, .nbz
Required BIOS| JiffyDOS_C128.bin, JiffyDOS_C64.bin, JiffyDOS_1541-II.bin, JiffyDOS_1571_repl310654.bin, JiffyDOS_1581.bin

## Commodore C64
Category|Information
:-------|:----------
Libretro Cores| Frodo, VICE x64 fast, VICE x64sc accurate
Format|.d64, .zip, .7z, .t64, .crt, .prg, .nib, .tap|
ES-DE Folder|c64

## Commodore C64 SuperCPU
Category|Information
:-------|:----------
Libretro Cores| VICE xscpu64
Format|.d64, d71, d80, d81, d82, g64, g41, x64, t64, tap, prg, p00, crt, bin, zip, gz, d6z, d7z, d8z, g6z, g4z, x6z, cmd, m3u, vfl, vsf, nib, nbz, d2m, d4m
Required BIOS| JiffyDOS_C64.bin, JiffyDOS_1541-II.bin, JiffyDOS_1571_repl310654.bin, JiffyDOS_1581.bin

## Commodore CBM-II 5x0
Category|Information
:-------|:----------
Libretro Cores| VICE xcbm5x0
Format|.d64, d71, d80, d81, d82, g64, g41, x64, t64, tap, prg, p00, crt, bin, zip, gz, d6z, d7z, d8z, g6z, g4z, x6z, cmd, m3u, vfl, vsf, nib, nbz, d2m, d4m|
ES-DE Folder|

## Commodore CBM-II 6x0/7x0
Category|Information
:-------|:----------
Libretro Cores| VICE xcbm2
Format|.d64, d71, d80, d81, d82, g64, g41, x64, t64, tap, prg, p00, crt, bin, zip, gz, d6z, d7z, d8z, g6z, g4z, x6z, cmd, m3u, vfl, vsf, nib, nbz, d2m, d4m|
ES-DE Folder|

## Commodore PET
Category|Information
:-------|:----------
Libretro Cores| VICE xpet
Format|.d64, .zip, .7z, .t64, .crt, .prg, .nib, .tap|
ES-DE Folder|

## Commodore PLUS/4
Category|Information
:-------|:----------
Libretro Cores| xplus4
Format|.d64, d71, d80, d81, d82, g64, g41, x64, t64, tap, prg, p00, crt, bin, zip, gz, d6z, d7z, d8z, g6z, g4z, x6z, cmd, m3u, vfl, vsf, nib, nbz, d2m, d4m|
ES-DE Folder|plus4

## Commodore VICE-20
Category|Information
:-------|:----------
Libretro Cores| VICE xvic
Format|.d64, .zip, .7z, .t64, .crt, .prg, .nib, .tap|

## Doom
Category|Information
:-------|:----------
Libretro Cores| PRBoom
Format|.wad, .iwad, .pwad|
ES-DE Folder|doom

## DOS
Category|Information
:-------|:----------
Libretro Cores| DOSBox-core, DOSBox-Pure, DOSBox-SVN 
Standalone Emulators| DosBox Turbo, AnDOSBox, Magic Dosbox, aDOSBox
Format|.dosz, .exe, .com, .img, .m3u, .bat, .conf, .cue, .zip|
ES-DE Folder|dos
ES-DE Folder (Alt)|windows3x
ES-DE Folder (Alt)|windows9x

## Fairchild ChannelIF
Category|Information
:-------|:----------
Libretro Cores| FreeChaFFormat|.bin, .rom, .chf, .zip
Required BIOS| sl31253.bin, sl31254.bin, sl90025.bin
ES-DE Folder|channelf

## Famicom Disk System
Category|Information
:-------|:----------
Libretro Cores| FCEUmm, Mesen, Nestopia UE
Standalone| NES.emu, iNES, Nesoid
Format|.fds, .zip, .7z
ES-DE Folder|fds
Required BIOS| disksys.rom

## GCE Vectrex
Category|Information
:-------|:----------
Libretro Cores| VecX
Standalone| MAME4droid 2024
ES-DE Folder|vectrex
Format|.vec, .zip, .7z

## Handheld Electronic
Category|Information
:-------|:----------
Libretro Cores| GW, MESS
Standalone| MAME4droid 2024
Format|.mgw, .zip, .7z
ES-DE Folder|lcdgames

## Java ME
Category|Information
:-------|:----------
Libretro Cores| SquirrelJME
Standalone| J2ME Loader, JL-Mod
Format|.jar, .sqc, .jam, .jad, .kjx
ES-DE Folder|j2me
Required BIOS| squirreljme.sqc

## LowRes NX
Category|Information
:-------|:----------
Libretro Cores| LowRes NX
Format|.nx|
ES-DE Folder|lowresnx

## Lua Engine
Category|Information
:-------|:----------
Libretro Cores| Lutro
Format|.lutro, .love, .lua|
ES-DE Folder|lutro

## Mac II
Category|Information
:-------|:----------
Libretro Cores| minivmac
Format|.dsk, .img, .zip, .hvf, .cmd
Required BIOS| MacII.ROM

## Magnavox Odyssey 2
Category|Information
:-------|:----------
Libretro Cores| O2EM
Standalone| MAME4droid 2024
Format|.bin
ES-DE Folder|odyssey2
Required BIOS| o2rom.bin, c52.bin, g7400.bin, jopac.bin

## Mattel Intellivision
Category|Information
:-------|:----------
Libretro Cores| FreeIntv
Standalone| MAME4droid 2024
Format|.bin, .int, .zip, .7z
ES-DE Folder|intellivision
Required BIOS| exec.bin, grom.bin

## Mega Duck/Cougar Boy
Category|Information
:-------|:----------
Libretro Cores| SameDuck
Standalone| MAME4droid 2024
Format|.bin, .zip, .7z|
ES-DE Folder|megaduck

## MSX
Category|Information
:-------|:----------
Libretro Cores| blueMSX, fMSX
Standalone| MSX.emu
Format|.cas, .dsk, .mx1, .mx2, .rom, .zip, .7z
ES-DE Folder|msx1
ES-DE Folder (Alt)|msx
BIOS Folder Name|`RetroArch\system\Databases\*`, `RetroArch\system\Machines\*`
Required BIOS| [blueMSX](http://bluemsx.msxblue.com/download.html)

## MSX2
Category|Information
:-------|:----------
Libretro Cores| blueMSX, fMSX
Standalone| fMSX, MSX.emu
Format|.cas, .dsk, .mx1, .mx2, .rom, .zip, .7z
ES-DE Folder|msx2
BIOS Folder Name|`RetroArch\system\Databases\*`, `RetroArch\system\Machines\*`
Required BIOS| [blueMSX](http://bluemsx.msxblue.com/download.html)

## NEC PC Engine
Category|Information
:-------|:----------
Libretro Cores| Beetle PCE Fast, Beetle SuperGrafx, PceEmu
Format|.pce, .zip, .7z|
ES-DE Folder|pcengine
ES-DE Folder (Japan)|tg16

## NEC PC Engine CD
Category|Information
:-------|:----------
Libretro Cores| Beetle PCE, Beetle PCE Fast, PceEmu
Format|.pce, .ccd, .iso, .img, .chd, .cue
ES-DE Folder|pcenginecd
ES-DE Folder (Japan)|tg-cd
Required BIOS| syscard3.pce _**Optional:**_ gexpress.pce, syscard1.pce, syscard2.pce

## NEC PC-8800
Category|Information
:-------|:----------
Libretro Cores| QUASI88
Format|.d88, .u88, .m3u
ES-DE Folder|pc88
BIOS Folder Name|`RetroArch\system\quasi88\`
Required BIOS| DISK.ROM, FONT.ROM, n88.rom, n88_0.rom, n88_1.rom, n88_2.rom, n88_3.rom, n88jisho.rom, n88knj1.rom, n88knj2.rom, n88n.rom, n88sub.rom

## NEC PC-98
Category|Information
:-------|:----------
Libretro Cores| Neko Project II Kai, Neko Project II
Format|.d88, .fdi, .hdi, .zip
ES-DE Folder|pc98
BIOS Folder Name|`RetroArch\system\np2kai\`
Required BIOS| font.bmp, FONT.ROM, bios.rom, itf.rom, sound.rom, bios9821.rom, d8000.rom, 2608_BD.WAV, 2608_SD.WAV, 2608_TOP.WAV, 2608_HH.WAV, 2608_TOM.WAV, 2608_RIM.WAV

## NEC PC-FX
Category|Information
:-------|:----------
Libretro Cores| Beetle PC-FX
Format|.chd, .zip, .cue, .ccd, .toc
ES-DE Folder|pcfx
Required BIOS| pcfx.rom

## Nintendo 3DS
Category|Information
:-------|:----------
Standalone Emulators| Citra, Citra Enhanced, Citra MMJ, Lemonade, Lime3DS, Mandarine, Panda3DS
Format|.3ds, .3dsx|
ES-DE Folder|n3ds

## Nintendo 64
Category|Information
:-------|:----------
Libretro Cores| Mupen64Plus-Next GLES3, ParaLLEI 
Standalone Emulators| M64Plus FZ
Format|.z64, .n64, .v64, .zip|
ES-DE Folder|n64

## Nintendo DS
Category|Information
:-------|:----------
Libretro Cores| DeSmuME, DeSmuME 2015, melonDS, melondDS DS
Standalone Emulators| Drastic, DeeS, melonDS, melonDS-Nightly, noods
Format|.nds, .zip
ES-DE Folder|nds
Required BIOS|_**Required for MelonDS or DeSmuME:**_ nds_bios_arm7.bin, nds_bios_arm9.bin, bios7.bin, bios9.bin|

## Nintendo DSi
Category|Information
:-------|:----------
Libretro Cores| melonDS, melondDS DS
Standalone Emulators| melonDS, melonDS-Nightly
Format|.dsi, .nds, .zip
Required BIOS|bios7.bin, bios9.bin, firmware.bin, nand.bin, dsi_bios7.bin, dsi_bios9.bin, dsi_firmware.bin, dsi_nand.bin|

## Nintendo Entertainment System
Category|Information
:-------|:----------
Libretro Cores| FCEUmm, Messen, Nestopia UE, QuickNES
Standalone| NES.emu, iNES, Nesoid
Format|.nes, .zip, .7z|
ES-DE Folder|nes
ES-DE Folder (Japan)|famicom

## Nintendo GameBoy Advance
Category|Information
:-------|:----------
Libretro Cores| gpSP, mGBA, VBA Next, VBA-M 
Standalone Emulators| Pizza Boy GBA, MyBoy!
Format|.gba, .zip, .7z
ES-DE Folder|gba
Optional BIOS| gba_bios.bin

## Nintendo GameBoy
Category|Information
:-------|:----------
Libretro Cores| Gambatte, Gearboy, mGBA, Messen-S, TGB Dual, VBA-M
Format|.gb, .gbc, .dmg, .zip, .7z
ES-DE Folder|gb
Optional BIOS| gb_bios.bin, sgb_bios.bin

## Nintendo GameBoy Color
Category|Information
:-------|:----------
Libretro Cores| Gambatte, Gearboy, mGBA, Messen-S, TGB Dual, VBA-M
Format|.gbc, .gb, .dmg, .zip, .7z
ES-DE Folder|gbc
Optional BIOS| gbc_bios.bin, sgb_bios.bin

## Nintendo Gamecube
Category|Information
:-------|:----------
Standalone Emulators| Dolphin, Dolphin MMJ, Dolphin MMJR, Dolphin MMJR2, Dolphin MMJR3
Format|.iso, .gcz, .rvz, .nkit|
ES-DE Folder|gc

## Nintendo Pokemon Mini
Category|Information
:-------|:----------
Libretro Cores| PokeMini
Format|.min, .zip
ES-DE Folder|pokemini
Optional BIOS| bios.min

## Nintendo Satellaview
Category|Information
:-------|:----------
Libretro Cores| Beetle Supafraust, bsnes, bsnes-jg, bsnes-mercury (Balanced), bsnes-mercury (Performance), Messen-S, Snes9x 2002, Snes9x 2005, Snes9x 2005 Plus, Snes9x 2010 
Standalone Emulators| Snes9x EX+
Format|.bs, .bsx, .smc, .sfc, .zip, .7z
ES-DE Folder|satellaview
Required BIOS|BS-X.bin

## Nintendo SNES
Category|Information
:-------|:----------
Libretro Cores| Beetle Supafraust, bsnes, bsnes-jg, bsnes-mercury (Balanced), bsnes-mercury (Performance), Messen-S, Snes9x 2002, Snes9x 2005, Snes9x 2005 Plus, Snes9x 2010 
Standalone Emulators| Snes9x EX+, SuperRetro16, SNESDroid, MultiSneS16, EmuSNES XL
Format|.smc, .sfc, .zip, .7z
ES-DE Folder|snes
ES-DE Folder (NA)|snesna
ES-DE Folder (Japan)|sfc

## Nintendo Switch
Category|Information
:-------|:----------
Standalone Emulators| Yuzu, Sudachi, Suyu, Strato, Skyline
Format|.nro, .nso, .nca, .xci, .nsp
ES-DE Folder|switch
Required BIOS|prod.keys, title.keys

## Nintendo Virtual Boy
Category|Information
:-------|:----------
Libretro Cores| Beetle VB
Standalone| Virtual Virtual Boy
Format|.vb, .vboy, .zip, .7z|
ES-DE Folder|virtualboy

## Nintendo Wii
Category|Information
:-------|:----------
Standalone Emulators| Dolphin, Dolphin MMJ, Dolphin MMJR, Dolphin MMJR2, Dolphin MMJR3
Format|.iso, .rvz, .nkit|
ES-DE Folder|wii

## Nintendo WiiU
Category|Information
:-------|:----------
Standalone Emulators|Cemu
Format|.rpx, .wua, .wux
ES-DE Folder|wiiu

## Oberon RISC Emulator
Category|Information
:-------|:----------
Libretro Cores| Oberon RISC Emulator
Format|.dsk|

## Palm OS
Category|Information
:-------|:----------
Libretro Cores| Mu, O2EM
Format|.prc, .pqa, .img, .pdb
ES-DE Folder|palm
Required BIOS| palmos41-en-m515.rom

## Philips CDi
Category|Information
:-------|:----------
Libretro Cores| SAME CDi
Standalone|MAME4droid 2024
Format|.chd, .iso
ES-DE Folder|cdimono1
BIOS Folder Name|`RetroArch\system\same_cdi\bios\`
Required BIOS| cdimono1.zip, cdimono2.zip, cdibios.zip

## Pico-8
Category|Information
:-------|:----------
Libretro Cores|  Retro8, Fake-08
Standalone Emulators| P8 Player, Infinity
Format|.png, .p8
ES-DE Folder|pico8

## RPG Maker 2000/2003
Category|Information
:-------|:----------
Libretro Cores| EasyRPG
Standalone Emulators| EasyRPG
Format|.ldb, .zip, .easyrpg
ES-DE Folder|easyrpg

## RPG Maker XP/VX/VA/MV
Category|Information
:-------|:----------
Standalone Emulators| Neko RPGXP Player, Joiplay
Required BIOS|Various|

## Sammy Atomiswave
Category|Information
:-------|:----------
Libretro Cores| Flycast 
Standalone Emulators| Redream, Flycast
Format|.chd, .ist, .bin, .zip
ES-DE Folder|atomiswave
BIOS Folder Name (Flycast-lr)|`RetroArch\system\dc\`
Required BIOS| awbios.zip

## ScummVM
Category|Information
:-------|:----------
Libretro Cores| ScummVM 
Standalone Emulators| ScummVM
Format|.zip, .scummvm|
ES-DE Folder|scummvm

## Sega 32X
Category|Information
:-------|:----------
Libretro Cores| PicoDrive
Format|.32x, .7z, .bin, .md, .smd, .zip|
ES-DE Folder|sega32x
ES-DE Folder (NA)|sega32xna
ES-DE Folder (Japan)|sega32xjp

## Sega CD/Mega CD
Category|Information
:-------|:----------
Libretro Cores| Genesis Plus GX, Genesis Plus GX Wide, PicoDrive
Standalone Emulators|MD.emu
Format|.chd, .bin/cue
ES-DE Folder|segacd
ES-DE Folder (Europe)|megacd
Required BIOS| bios_CD_U.bin, bios_CD_E.bin, bios_CD_J.bin

## Sega Dreamcast
Category|Information
:-------|:----------
Libretro Cores| Flycast 
Standalone Emulators| Flycast, Redream, Reicast
Format|.chd, .bin/.cue, .bin/.gdi, .bin/cdi
ES-DE Folder|dreamcast
BIOS Folder Name (Flycast-lr)|`RetroArch\system\dc\`
Required BIOS|_**Required for Flycast:**_ dc_boot.bin, dc_flash.bin

## Sega Game Gear
Category|Information
:-------|:----------
Libretro Cores| Gearsystem, Genesis Plus GX, Genesis Plus GX-Wide, Gearsystem, SMS Plus GX, PicoDrive
Standalone| Pizza Boy SC, MasterGear
Format|.gg, .bin, .zip, .7z
ES-DE Folder|gamegear
Optional BIOS| bios.gg

## Sega Genesis/MegaDrive
Category|Information
:-------|:----------
Libretro Cores| Genesis Plus GX, Genesis Plus GX Wide, PicoDrive
Format|.md, .68k, .mdx, .sgd, .smd, .gen, .bin, .zip, .7z
ES-DE Folder|genesis
ES-DE Folder|megadrive
ES-DE Fodler (Japan)|megadrivejp
Optional BIOS| bios_MD.bin

## Sega Master System
Category|Information
:-------|:----------
Libretro Cores| Gearsystem, Genesis Plus GX, Genesis Plus GX Wide, PicoDrive
Standalone| Pizza Boy SC, MasterGear, MD.emu
Format|.7z, .bin, .sms, .zip
ES-DE Folder|mastersystem
Optional BIOS| bios_E.sms, bios_U.sms, bios_J.sms

## Sega Naomi
Category|Information
:-------|:----------
Libretro Cores| Flycast 
Standalone Emulators| Flycast
Format|.dat, .ist, .bin, .chd/.zip
ES-DE Folder|naomi
BIOS Folder Name (Flycast-lr)|`RetroArch\system\dc\`
Required BIOS| naomi.zip, hod2bios.zip, f355dlx.zip, f355bios.zip, airlbios.zip

## Sega Naomi 2
Category|Information
:-------|:----------
Libretro Cores| Flycast 
Standalone Emulators| Flycast
Format|.chd/.zip
ES-DE Folder|naomi2
BIOS Folder Name (Flycast-lr)|`RetroArch\system\dc\`
Required BIOS| naomi2.zip

## Sega Saturn
Category|Information
:-------|:----------
Libretro Cores| Beetle Saturn, YabaSanshiro, Yabause 
Standalone Emulators| YabaSanshiro, YabaSanshiro 2, YabaSanshiro 2 Pro, Saturn.emu
Format|.chd, .iso, .bin/.cue
ES-DE Folder|saturn
ES-DE Folder (Japan)|saturnjp
Required BIOS|_**Required for Beetle-Saturn:**_ sega_101.bin, mpr-17933.bin, mpr-18811-mx.ic1, mpr-19367-mx.ic1 _**Optional:**_ saturn_bios.bin

## Sega SG-1000
Category|Information
:-------|:----------
Libretro Cores| Gearsystem, Genesis Plus GX, Genesis Plus GX Wide, blueMSX
Format|.7z, .bin, .sg, .zip
ES-DE Folder|sg-1000
ES-DE Folder (Clone/Regional)|multivision
BIOS Folder Name|`RetroArch\system\Databases\*`, `RetroArch\system\Machines\*`
Required BIOS| [blueMSX](http://bluemsx.msxblue.com/download.html)

## Sega VMU
Category|Information
:-------|:----------
Libretro Cores| VeMUlator
Format|.vms, .bin

## Sharp X1
Category|Information
:-------|:----------
Libretro Cores| X Millennium
Format|.dx1, .zip, .2d, .2hd, .tfd, .d88, .88d, .hdm, .xdf, .dup, .cmd
ES-DE Folder|x1
BIOS Folder Name|`RetroArch\system\xmil\`
Required BIOS| IPLROM.X1, IPLROM.X1T

## Sharp X68000
Category|Information
:-------|:----------
Libretro Cores| PX68k
Format|.dim, .m3u
ES-DE Folder|x68000
BIOS Folder Name|`RetroArch\system\keropi\`
Required BIOS| iplrom.dat, cgrom.dat, iplrom30.dat, iplromco.dat, iplromxv.dat

## Sinclair ZX 81
Category|Information
:-------|:----------
Libretro Cores| EightyOne
Format|.p, .tzx, .zip
ES-DE Folder|zx81

## Sinclair ZX Spectrum
Category|Information
:-------|:----------
Libretro Cores| Fuse
Format|.sna, .szx, .z80, .tap, .tzx, .gz, .udi, .mgt, .img, .trd, .scl, .dsk|
ES-DE Folder|zxspectrum

## SNK Neo Geo CD
Category|Information
:-------|:----------
Libretro Cores| Final Burn Neo, NeoCD, Geolith
Format|.bin/.cue, .chd
ES-DE Folder|neogeocd
BIOS Folder Name (Final Burn Neo)|`RetroArch\system\fbneo\`
BIOS Folder Name (NeoCD-lr)|`RetroArch\system\neocd\`
Required BIOS| neocd_f.rom, neocd_sf.rom, front-sp1.bin, neocd_t.rom, neocd_st.rom, top-sp1.bin, neocd_z.rom, neocd_sz.rom, neocd.bin, ng-lo.rom, 000-lo.lo, uni-bioscd.rom, neocd.zip

<details>
<summary>Final Burn Neo subsystem information</summary>
<br>

* For NeoGeo CD to work on Final Burn Neo the roms need to be placed in a `neocd\` folder
* Example:

> roms\neocd\King of Fighters '98, The - Dream Match Never Ends ~ The King of Fighters '98 - The Slugfest (Japan) (En,Ja).bin

> roms\neocd\King of Fighters '98, The - Dream Match Never Ends ~ The King of Fighters '98 - The Slugfest (Japan) (En,Ja).cue

</details>

## SNK Neo Geo Pocket
Category|Information
:-------|:----------
Libretro Cores| Beetle NeoPop, RACE
Format|.ngp, .ngc, .zip, .7z|
ES-DE Folder|ngp

## Sony PlayStation
Category|Information
:-------|:----------
Libretro Cores| Beetle PSX HW, Beetle PSX, PCSX-ReArmed, SwanStation 
Standalone Emulators| Avocado, DuckStation,  ePSXe, FPse, XEBRA
Format|.chd, .pbp, .bin/.cue, .m3u
ES-DE Folder|psx
Required BIOS| scph5500.bin, scph5501.bin, scph5502.bin, psxonpsp660.bin

## Sony PlayStation 2
Category|Information
:-------|:----------
Standalone Emulators| AetherSX2, NetherSX2
Format|.iso, .chd, .bin/cue
ES-DE Folder|ps2
Required BIOS| Any 4MB PS2 bios in .bin format

## Sony PlayStation Portable
Category|Information
:-------|:----------
Libretro Cores| PPSSPP 
Standalone Emulators| PPSSPP, PPSSPP-Gold
Format|.iso, .cso, .pbp, .chd|
ES-DE Folder|psp

## Sony PlayStation Vita
Category|Information
:-------|:----------
Standalone Emulators| Vita3k
Format|.pkg, .zip, .vpk
ES-DE Folder|psvita
Required BIOS|PSVUPDAT.PUP, PSP2UPDAT.PUP

## Thomson MO/TO
Category|Information
:-------|:----------
Libretro Cores| Theodore
Format|.fd, .sap, .k7, .m7, .m5, .rom|
ES-DE Folder|to8

## TIC-80
Category|Information
:-------|:----------
Libretro Cores| TIC-80
Format|.tic|
ES-DE Folder|tic80

## Uzebox
Category|Information
:-------|:----------
Libretro Cores| Uzem
Format|.uze|
ES-DE Folder|uzebox

## VaporSpec
Category|Information
:-------|:----------
Libretro Cores| VaporSpec
Format|.vaporbin|

## WASM-4
Category|Information
:-------|:----------
Libretro Cores| WASM4
Format|.wasm|
ES-DE Folder|wasm4

## Watara Supervision
Category|Information
:-------|:----------
Libretro Cores| Potator
Format|.bin, .sv|
ES-DE Folder|supervision

## Wolfenstein 3D
Category|Information
:-------|:----------
Libretro Cores| ECWolf
Format|.wl6, .n3d, .sod, .sdm, .wl1, .pk3, .exe
Required BIOS| ecwolf.pk3
ES-DE Folder|ports

# M3U Files

### M3U File Generator python script

* [M3U File Generator python script](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/M3UGenerator.py) (Right-Click > Download)

1. Place script inside folder you want to generate m3u
2. Select one of the options
3. Click `Submit`

### Setup 1

<details>
<summary>Setup 1: M3U file normal usage</summary>
<br>

The `.m3u` format is a playlist file. It's highly recommended to use `.m3u` files for your multi disc games. They are simple to create too:

1. Create a text file

2. Rename `.txt` to `.m3u`

3. Open the `.m3u` and add your disc to each line

> Example 1
```
Chrono Cross (USA) (Disc 1).chd
Chrono Cross (USA) (Disc 2).chd
```

> Example 2
```
Final Fantasy IX (USA) (Disc 1).cue
Final Fantasy IX (USA) (Disc 2).cue
Final Fantasy IX (USA) (Disc 3).cue
Final Fantasy IX (USA) (Disc 4).cue
```

4. Save file and place in the same folder as the content

</details>

### Setup 2

<details>
<summary>Setup 2: M3U file with content in other folders</summary>
<br>

You can also have your content in different folders. This is useful for front-ends that might scan disc and m3u files, leading to multiple files. Simply write the path to the content in the m3u files.

1. Let's say you typically place your psx games in `/roms/psx/`.

2. Now create a folder outside the psx folder. Let's name it `psxmutltidisc`.

3. As an example lets use Metal Gear Solid and place each disc in the newly created folder `/roms/psxmultidisc/` folder. 

4. Now you can simply write your m3u file exactly as such:

```
../psxmultidisc/Metal Gear Solid (USA) (Disc 1) (Rev 1).chd
../psxmultidisc/Metal Gear Solid (USA) (Disc 2) (Rev 1).chd
```

5. Save and place the file in our example folder `/roms/psx/`

Now your preferred front-end will only scan and show one file instead of three (in this case).

</details>

### Setup 3

<details>
<summary>Setup 3: M3U file with content in another folder for Duckstation</summary>
<br>

DuckStation requires URI paths if file is in a seperate directory.

* Ensure DuckStation has permissions to the multidisc folder

> Duckstation > ≡ > App Settings > Game List > Add Folder

* You can quickly find out the path to the file in the menu above after adding the folder

We'll use these paths in examples shown:

Path|Note
:---|:---|
roms/psx/|Path of your normal psx games & m3u files
roms/psxmulti/|Path of multidisc psx games

* URI Path Example for `roms/psxmulti/`

Path|Note
:---|:---|
`content://com.android.externalstorage.documents/tree/primary:roms%2Fpsxmulti/document/primary:roms%2Fpsxmulti%2F`|Internal Storage
`content://com.android.externalstorage.documents/tree/STRINGOFNUMBERS&LETTERS:roms%2Fpsxmulti/document/STRINGOFNUMBERS&LETTERS:roms%2Fpsxmulti%2F`|Replace `STRINGOFNUMBERS&LETTERS` with your own

* Cheat Sheet:

Character|Encoded character|Note
:--------|:----------------|:----
`:`|`%3A`|Either character can be used
`/`|`%2F`|Encoded character is required 
Space|`%20`|Either character can be used

Examples

Path|Note
:---|:---
roms/psx/Chrono Cross (USA).m3u|
roms/psxmulti/Chrono Cross (USA) (Disc 1).chd|
roms/psxmulti/Chrono Cross (USA) (Disc 2).chd|
`content://com.android.externalstorage.documents/tree/primary:roms%2Fpsxmulti/document/primary:roms%2Fpsxmulti%2FChrono Cross (USA) (Disc 1).chd`|m3u file line 1
`content://com.android.externalstorage.documents/tree/primary:roms%2Fpsxmulti/document/primary:roms%2Fpsxmulti%2FChrono Cross (USA) (Disc 2).chd`|m3u file line 2

_The M3U file will not work for anything but DuckStation._

</details>

### Setup 4

<details>
<summary>Setup 4: ES-DE M3U files</summary>
<br>

ES-DE can have [directories interpreted as files](https://gitlab.com/es-de/emulationstation-de/-/blob/master/USERGUIDE.md?ref_type=heads#directories-interpreted-as-files). This a a very convenient method to hide multidisc games and show only one entry.

* The name of the folder will dictate the file that will be loaded. 

Path/File|Note
:------|:----
`/roms/psx/Microwaved Banana (Japan).m3u/`|Folder Name
`/roms/psx/Microwaved Banana (Japan).m3u/Microwaved Banana (Japan).m3u`|m3u file
`/roms/psx/Microwaved Banana (Japan).m3u/Microwaved Banana (Japan) (Disc 1).chd`|
`/roms/psx/Microwaved Banana (Japan).m3u/Microwaved Banana (Japan) (Disc 2).chd`|

> M3U file contents
```
Microwaved Banana (Japan) (Disc 1).chd
Microwaved Banana (Japan) (Disc 2).chd
```
</details>

### Setup 5

<details>
<summary>Setup 5: M3U files for Dolphin</summary>
<br>

Some versions of Dolphin support M3U files. Official Dolphin dev build worked when tested

* Paths must be hardcoded
* M3U files should use Unix line endings
* If using external folder such as the example Setup 2 or 3, the folder must be added to Dolphin

Let's use `roms/gc/` as the example base folder while `roms/gcmulti/` as the example for multidisc folder

Path/File|Note
:------|:----
`roms/gc/Metal Gear Solid - The Twin Snakes (USA).m3u`|
`roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 1).rvz`
`roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 2).rvz`

For the M3U files content you need hardcoded paths with storage path:

Storage|Path|Note
:------|:---|:----
Internal|`/storage/emulated/0/`|
SD Card|`/storage/XXXX-XXXX/`|Replace `XXXX-XXXX` with your SD cards unique ID


> Internal Storage example Metal Gear Solid - The Twin Snakes (USA).m3u
```
/storage/emulated/0/roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 1).rvz
/storage/emulated/0/roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 2).rvz
```

> SD Card example Metal Gear Solid - The Twin Snakes (USA).m3u
```
/storage/3731-3730/roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 1).rvz
/storage/3731-3730/roms/gcmulti/Metal Gear Solid - The Twin Snakes (USA) (Disc 2).rvz
```
</details>

# MESS

### MESS File Generator script

Needed|Info/Folder
:-----|:----
MESS|RetroArch Core
MAME|RetroArch Core
[MAME Hash files](https://github.com/mamedev/mame/tree/master/hash)|RetroArch/systems/mame/hash
[MAMEHashConverter](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/MAMEHashConverter.py)

1. Download and place the hash xml files into a folder called hash
2. Open MAMEHashCovrter.py > Select hash folder > Generate cmd > enter details > copy folder to device

_Note that the generate cmd only works for certain xml files so far_

# Moonlight Files

### Moonlight File Generator script

Needed|Info
:-----|:----
[Moonlight (Portable)](https://github.com/moonlight-stream/moonlight-qt/releases)|
[Moonlight Android](https://play.google.com/store/apps/details?id=com.limelight)|
[Moonlight File Generator Script](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/MoonlightFileGenerator.py)|Right Click > Download Link

Steps|Tips
:----|:----
Download Moonlight Portable|
Extract zip > launch Moonlight.exe > Link PC with device
Install Moonlight on Android > Link PC
Run MoonlightFileGenerator.py > Locate Moonlight.ini within Moonlight portable folder|*\Moonlight Game Streaming Project\Moonlight.ini
Select button based on frontend being used

### Daijishou Moonlight

<details>
<summary>Daijishou Moonlight Setup</summary>
<br>

1. Select "Create Daijishou Moonlight files"
2. Copy the moonlight folder and files it generated near your Moonlight.ini folder to your device
3. Import Moonlight.json platform within [Daijishou](https://github.com/TapiocaFox/Daijishou/wiki/How-to-Use-Daijish%C5%8D#adding-platforms-manually)
4. Add moonlight folder path to Moonlight platform

</details>

### ES-DE Moonlight

<details>
<summary>ES-DE Moonlight Setup</summary>
<br>

1. Select "Create ES-DE Moonlight files"
2. Copy the moonlight folder and files it generated near your Moonlight.ini folder to your device
3. Add Moonlight to your `es_find_rules.xml` and `es_system.xml`

> es_find_rules.xml

```
    <emulator name="Moonlight">
        <rule type="androidpackage">
            <entry>com.limelight/com.limelight.ShortcutTrampoline</entry>
        </rule>
    </emulator>
```

> es_system.xml

```
    <system>
        <name>moonlight</name>
        <fullname>Moonlight Game Streaming</fullname>
        <path>%ROMPATH%/moonlight</path>
        <extension>.moonlight</extension>
        <command label="Moonlight">%EMULATOR_Moonlight% %EXTRA_UUID%=%INJECT%=Moonlight.uuid %EXTRA_AppId%=%INJECT%=%BASENAME%.moonlight</command>
        <platform>moonlight</platform>
        <theme>moonlight</theme>
    </system>
```

</details>


# MSU-1 Files

For MSU-1 to properly work:
* All files need to have a common file name.
* All files need to be in the same folder. 

One patch file can be kept in the same folder if you want to utilize [soft patching](https://github.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/wiki/RetroArch#softpatching) features. Otherwise patch the game with a [patcher](https://github.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/wiki/Useful-Programs#patching-games). 

`EarthBound (USA)` will be the common file name in the example below:

File                   |Note
:----------------------|:-----
EarthBound (USA).bps   |Patch file. Only need 1 patch file.
EarthBound (USA).ips   |Patch file. Only need 1 patch file.
EarthBound (USA).msu   |MSU file.
EarthBound (USA).sfc   |Game file.
EarthBound (USA)-*.pcm |Music file.

* [MSU1 Rename Scripts](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/MSU1Renamer.py) (Right-Click > Download)
* The script will rename the .bps, .ips, .msu, and .pcm files after the .sfc file
* The script will look in the same folder or sub-folders
* If renaming multiple games create sub-folders for each game

1. Place the script in the same folder as the `.sfc` and `.pcm` files
2. Run script

# NES HD Packs

1. Use Mesen core
2. Create `HdPacks/` folder in `RetroArch/system/`
3. Rename HD Pack after the name of rom (Example: `Legend of Zelda, The (USA).zip` = `Legend of Zelda, The (USA)/`)
4. Place HD Pack inside `RetroArch/system/HdPacks/` folder
5. Enable HD packs within core options (RetroArch Quick Menu > Core Options > Enable HD Packs)

# ScummVM File Generator

Download|
:-------|
[ScummVM File Generator](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/ScummvmGen.py)|
[ScummVM.dat](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-3-Plus-Wiki/main/Files/Backup/ScummVM.dat)|
[ScummVM Daily Builds](https://buildbot.scummvm.org/#/dailybuilds)|

1. Start python script
2. Select button for frontend
3. Select Scummvm.dat
4. Copy files to device
5. Install ScummVM Daily build
6. Add game to ScummVM as normal

# Vita3k Frontend Support

Progenerated Launcher File Downloads|
:-------|
[Daijishou .dpt Files](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-4-Pro-Wiki/main/Files/vitadpt.zip)
[ES-DE .psvita Files](https://raw.githubusercontent.com/Jetup13/Retroid-Pocket-4-Pro-Wiki/main/Files/psvitaesde.zip)

Daijishou Example:

> 7'scarlet (USA) (Card).dpt

```
# Daijishou Player Template
[vita_game_id] PCSE01168
...
```

ES-DE Example:

> 7'scarlet (USA) (Card).psvita

```
PCSE01168
```

