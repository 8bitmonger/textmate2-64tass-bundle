This is a fork of [textmate2-64tass-bundle](https://github.com/vigo/textmate2-64tass-bundle), which was originally publised by [Uğur "vigo" Özyılmazel](https://github.com/vigo). 

The aim of this work is to make the plugin compatible with [Xemu](https://github.com/lgblgblgb/xemu).

## Major changes

1: The output is assembled into the project directory instead of a temporary location.

2: Requirement for VICE has been removed (might be added back later).

3: The default parameters will target CSG 4510.

## Installation

1: Clone the repository directly into the TextMate bundles folder (~/Library/Application\ Support/TextMate/Bundles/) as C64TassXEMU.tmbundle.

2: Restart TextMate.


## Requirements

[64tass assembler](http://tass64.sourceforge.net/) (bundled)

### Optional Settings

No further configuration is needed. However, there are a few optional environment variables that can be defined if desired.

`TM_64TASS_OPTIONS` can be used to override the default 64tass options (-a --m4510).
`TM_64TASS_PATH` can be used to override the bundled 64tass version (**64tass Turbo Assembler Macro V1.52.1237?**).

## License

This project is licensed under MIT
