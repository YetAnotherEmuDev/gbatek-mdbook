# Consoles 

## Original Gameboy Advance (GBA)

```
      ____._____________...___.____
 ____/    :  CARTRIDGE  SIO   :    \____
| L       _____________________  LED  R |
|        |                     |        |
|  _||_  |   2.9" TFT SCREEN   |    (A) |
| |_  _| | 240x160pix  61x40mm | (B)    |
|   ||   |    NO BACKLIGHT     |  ::::  |
|        |                     | SPEAKR |
| STRT() |_____________________|  ::::  |
| SLCT()     GAME BOY ADVANCE    VOLUME |
|____  OFF-ON  BATTERY 2xAA PHONES  _==_|
     \__.##.__________________,,___/
```

## GBA SP (GBA SP)

Deluxe version of the original GBA. With backlight, new folded laptop-style case, and built-in rechargeable battery. Appears to be 100% compatible with GBA, there seems to be no way to detect SPs by software.

```
 _______________________                                   _
| _____________________ |                                 / /
||                     ||                                / /
||   2.9" TFT SCREEN   ||                               / /
|| 240x160pix  61x40mm ||                              / /
||   WITH BACKLIGHT    ||                             / /
||                     ||       GBA SP SIDE VIEWS    / /
||_____________________||                           / /
|  GAME BOY ADVANCE SP  |     _____________________(_)
|_______________________|    |. . . . . . . .'.'.   _|
|_|________|________|_|_|    |_CARTRIDGE_:_BATT._:_|_| <-- EXT1/EXT2
|L    EXT1     EXT2    R|  
|          (*)      LEDSo     _____________________ _
(VOL_||_           (A)  o    |_____________________(_)
|  |_  _| ,,,,,(B)      |    |. . . . . . . .'.'.   _|
|    ||   ;SPK;         |    |_CARTRIDGE_:_BATT._:_|_| <-- EXT1/EXT2
|         '''''      ON #                           _ _____________________
|       SLCT STRT    OFF#     _____________________(_)_____________________|
| CART.  ()   ()        |    |. . . . . . . .'.'.   _|
|_:___________________:_|    |_CARTRIDGE_:_BATT._:_|_| <-- EXT1/EXT2
```

## Gameboy Micro (GBA Micro)

Minituarized GBA. Supports 32bit GBA games only (no 8bit DMG/CGB games). The 256K Main RAM is a bit slower than usually (cannot be "overclocked" via port `0x4000800`).

```
 ________________SIO_______________
| L      __________________      R |
|       |     GBA-MICRO    |       |
| _||_  |  2.0" TFT SCREEN |    (A)| +
||_  _| |240x160pix 42x28mm| (B)   |VOL
|  ||   |     BACKLIGHT    |       | -
|       |__________________|  ...  |
|___________SELECT__START__________|
  PWR   <--- CARTRIDGE SLOT ---> PHONES
```

## Nintendo DS (NDS)

```
   _____________________________________
  |        _____________________        |
  |       |                     |       |
  |       |    3" TFT SCREEN    |       |
  |       | 256x192pix  61x46mm |       |
  |       |      BACKLIGHT      |       |
  | ::::: |    Original NDS     | ::::: |
  | ::::: |_____________________| ::::: |
 _|        _          ______   _        |_  <-- gap between screens: 22mm
|L|_______| |________|      |_| |_______|R|     (equivalent to 90 pixels)
|_______   _____________________   _______|
|  PWR  | |                     | |SEL STA|
|   _   | |    3" TFT SCREEN    | |       |
| _| |_ | | 256x192pix  61x46mm | |   X   |
||_   _|| |      BACKLIGHT      | | Y   A |
|  |_|  | |    TOUCH SCREEN     | |   B   |
|       | |_____________________| |       |
|_______|             NintendoDS  |_______|
|         MIC                LEDS         |
|_________________________________________|
     VOL        SLOT2(GBA)     MIC/PHONES
```

## Nintendo DS Lite (NDS-Lite)

New handheld with two screens, backwards compatible with GBA games, it is NOT backwards compatible with older 8bit games (mono/color gameboys) though.

Also, the DS has no link port, so that GBA games will thus work only in single player mode, link-port accessoires like printers cannot be used, and most unfortunately multiboot won't work (trying to press Select+Start at powerup will just lock up the DS).

```
  _____________________________________
 |        _____________________        |
 |       |                     |       |
 |       |    3" TFT SCREEN    |       |
 |  ...  | 256x192pix  61x46mm |  ...  |
 |  ...  |      BACKLIGHT      |  ...  |
 |       |      NDS-LITE       |       |
 |       |_____________________|       |
 |___  _ _ _ _ _ _ _ _ _ _ _ _ _ _ ____| <-- gap between screens: 23mm
L| _ |_____________MIC____________|LEDS|R
 |   _    _____________________        |
 | _| |_ |                     |   X   |
 ||_   _||    3" TFT SCREEN    | Y   A |PWR
 |  |_|  | 256x192pix  61x46mm |   B   |
 |       |      BACKLIGHT      |       |
 |       |    TOUCH SCREEN     |oSTART |
 |       |_____________________|oSELECT|
 |_____________________________________|
    VOL        SLOT2(GBA)     MIC/PHONES
```

## Nintendo DSi (DSi)

```
    _____________________________________
   |        _____________________        |
   |       |                     |   O o | <-- CAM (O) and LED (o)
   |       |   3.25" TFT SCREEN  |       |     (on backside)
   |       | 256x192pix  66x50mm |       |
   |       |      BACKLIGHT      |       |
   |  __   |         DSi         |   __  |
   | (__)  |_____________________|  (__) |
   |___  _ _ _ _ _ _ _ _ _ _ _ _ _ _ ____| <-- gap between screens: 23mm
  L|LEDS|__________CAM__MIC_________| __ |R                  (88 pixels)
 + |   _    _____________________        |
VOL| _| |_ |                     |   X   | <-- SD Card Slot
 - ||_   _||   3.25" TFT SCREEN  | Y   A |
   |  |_|  | 256x192pix  66x50mm |   B   |
   |       |      BACKLIGHT      |       |
   |       |    TOUCH SCREEN     |oSTART |
   | POWERo|_____________________|oSELECT|
   |_____________________________________|
                                MIC/PHONES
```

## Nintendo DSi XL

As DSi, but bigger case, and bigger 4.2" screens

## Gameboy Player (Gamecube Joypad) (GBA Player)

```
              _________
  L____-------         -------____R
  /   ___   \           /   (Y)   \Z
 /   / O \   | (START) |        (X)\     Z      = Gameboy Player Menu
|    \___/    \_______/      (A)    |    X or Y = Select button
|\         _   \     /    (B)      /|
| \___   _| |_  \   /   ___    ___/ |    optionally X/Y can be
|    |\ |_   _| /   \  / C \  /|    |    swapped with L/R (?)
|    | \  |_|  /     \ \___/ / |    |
|    |  \_____/       \_____/  |    |    analogue sticks = ?
 \__/                           \__/
```

## Gameboy Player (Gamecube Bongos) (GBA Player)

A GBA Adapter for the Gamecube console; allowing to play GBA games on a television set.

```
  _______     _______
 /   Y   \   /   X   \     Y/B = left bongo rear/front side
| . . . . |_| . . . . |    X/A = right bongo rear/front side
|    B    |R|    A    |    S   = start/pause button
|\_______/|_|\_______/|    R   = microphone (triggers R button)
|\_______/|S|\_______/|
|         |_|         |    (the X/Y inputs can be assigned to
|\_______/| |\_______/|    GBA R/L inputs in GBA player setup)
 \_______/   \_______/
```

> ### iQue
> iQue is a brand name used by Nintendo in China, iQue GBA and iQue DS are essentially same as Nintendo GBA and Nintendo DS.
> 
> The iQue DS contains a larger firmware chip (the charset additionally contains about 6700 simplified chinese characters), the bootmenu still allows to select (only) six languages (japanese has been replaced by chinese). The iQue DS can play normal international NDS games, plus chinese dedicated games. The latter ones won't work on normal NDS consoles (that, reportedly simply due to a firmware-version check contained in chinese dedicated games, aside from that check, the games should be fully compatible with NDS consoles).
