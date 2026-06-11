# Robot 64
the original game: https://roblox.com/games/1111083356/Robot-64  
raylib (used for this, specifically the itch.io installer): https://raylib.com  
*note: this project still uses raylib 5.5, an outdated version*  

# Credits
zKevin (roblox) for the original game (and letting me upload this to github)  
LuaW1z and UncagedTwistedMania (roblox) for the decomp this is based off of (and letting me uplaod aswell)

# Debug controls
Press `G` to noclip  
Press `H` to toggle jetpack  
Press `J` to toggle skateboard  
Press `L` to take damage

# Compiling

### Requirements
- windres

you have to build the rc data by running `windres robot64.rc -o robot64.rc.data` (required by all platforms)

## Windows

### Windows Requirements
- mingw64

run `make` in the repository directory

## Web

run the command found in "webcompilecommand.txt"

## Linux

### Linux Requirements
- gcc-15
- make

run `make` in the repository directory

its a little weird but it gets the jobb doen i guess  