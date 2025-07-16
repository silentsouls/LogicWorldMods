# Logic World Mods

### Silents file ROM

Add the filename in the text window, to load the file use the reset peg on the left
The component outputs 8bits at a time, and an EOF if the address goes past the data size
It can  address 16 bit. so do not make the files to large

pin layout:
on the top from left to right:
EOF then 8 bits (most right one is the least significant)
on the bottom
Reset, then 16 address pins (right one is the least significant)

#### HEX an MC
File extensions "Hex and MC" will result in parsing the file

### Mod install
Just copy the SilentsFileRom to the "\Logic World\GameData\" folder.
To support older versions of the game, simply rename manifest.jecs to manifest.succ, and "languages\English\English_components.jecs" to "languages\English\English_components.succ"


