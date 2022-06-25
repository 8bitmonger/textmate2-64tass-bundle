This is a fork of [textmate2-64tass-bundle](https://github.com/vigo/textmate2-64tass-bundle), which was originally publised by [Uğur "vigo" Özyılmazel](https://github.com/vigo). 

The aim of this work is to make the plugin compatible with [Xemu](https://github.com/lgblgblgb/xemu).

## Major changes

1: Xemu can be started automatically with the newly assembled PRG file

2: The output is assembled into the project directory instead of a temporary location

3: Dependency for VICE has been removed (option to use VICE might be added later)

4: The default parameters will target CSG 4510


## Installation

1: Clone the repository directly into the TextMate bundles folder (~/Library/Application\ Support/TextMate/Bundles/) as C64TassXemu.tmbundle

2: Restart TextMate

3: (Optional) define TM_XEMU_PATH to a fresh Xemu instance with the newly assembled PRG file

## Requirements

[64tass assembler](http://tass64.sourceforge.net/) (bundled)

### Optional Settings

No further configuration is needed. However, there are a few optional environment variables that can be defined if desired.
In particular, Xemu will launch with the newly assembled PRG file if TM_XEMU_PATH is defined. 
TM_XEMU_OPTIONS will default to -besure switch which makes it faster to work with the emulator.

`TM_XEMU_PATH` path to the Xemu executable (e.g. xmega65)
`TM_XEMU_OPTIONS` options for the Xemu executable; the assembled prg file is always included regardless of what is defined here
`TM_64TASS_OPTIONS` can be used to override the default 64tass options (-a --m4510).
`TM_64TASS_PATH` can be used to override the bundled 64tass version (**64tass Turbo Assembler Macro V1.52.1237?**).

## License

This project is licensed under MIT
