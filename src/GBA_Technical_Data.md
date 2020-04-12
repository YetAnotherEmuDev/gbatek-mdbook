# GBA Technical Data

## CPU Modes

- ARM Mode: ARM7TDMI 32bit RISC CPU, 16.78MHz, 32bit opcodes (GBA)
- THUMB Mode: ARM7TDMI 32bit RISC CPU, 16.78MHz, 16bit opcodes (GBA)
- CGB Mode: Z80/8080-style 8bit CPU, 4.2MHz or 8.4MHz (CGB compatibility)
- DMG Mode: Z80/8080-style 8bit CPU, 4.2MHz (monochrome gameboy compatib.)

The GBA's separate 8bit/32bit CPU modes cannot be operated simultaneously. Switching is allowed between ARM and THUMB modes only (that are the two GBA modes).
This manual does not describe CGB and DMG modes, both are completely different than GBA modes, and both cannot be accessed from inside of GBA modes anyways.

## Internal Memory

- BIOS ROM: 16 KBytes
- Work RAM: 288 KBytes (Fast 32K on-chip, plus Slow 256K on-board)
- VRAM: 96 KBytes
- OAM: 1 KByte (128 OBJs 3x16bit, 32 OBJ-Rotation/Scalings 4x16bit)
- Palette RAM: 1 KByte (256 BG colors, 256 OBJ colors)

## Video

- Display: 240x160 pixels (2.9 inch TFT color LCD display)
- BG layers: 4 background layers
- BG types: Tile/map based, or Bitmap based
- BG colors: 256 colors, or 16 colors/16 palettes, or 32768 colors
- OBJ colors: 256 colors, or 16 colors/16 palettes
- OBJ size: 12 types (in range 8x8 up to 64x64 dots)
- OBJs/Screen: max. 128 OBJs of any size (up to 64x64 dots each)
- OBJs/Line: max. 128 OBJs of 8x8 dots size (under best circumstances)
- Priorities: OBJ/OBJ: 0-127, OBJ/BG: 0-3, BG/BG: 0-3
- Effects: Rotation/Scaling, alpha blending, fade-in/out, mosaic, window
- Backlight: GBA SP only (optionally by light on/off toggle button)

## Sound

- Analogue: 4 channel CGB compatible (3x square wave, 1x noise)
- Digital: 2 DMA sound channels
- Output: Built-in speaker (mono), or headphones socket (stereo)

## Controls

- Gamepad: 4 Direction Keys, 6 Buttons

## Communication Ports

- Serial Port: Various transfer modes, 4-Player Link, Single Game Pak play

## External Memory

- GBA Game Pak: max. 32MB ROM or flash ROM + max 64K SRAM
- CGB Game Pak: max. 32KB ROM + 8KB SRAM (more memory requires banking)

## Case Dimensions (mm)

- GBA: 145x81x25
- GBA SP: 82x82x24 (closed), 155x82x24 (stretch)

## Power Supply

- Battery GBA: GBA: 2x1.5V DC (AA), Life-time approx. 15 hours
- Battery SP: GBA SP: Built-in rechargeable Lithium ion battery, 3.7V 600mAh
- External: GBA: 3.3V DC 350mA - GBA SP: 5.2V DC 320mA
