# CS:GO Config
Just my CS:GO config...

For now, the config and video files should be placed into (depending on application installation drive):

### Windows
`C:\Program Files (x86)\Steam\userdata\<steam_account_id>\730\local\cfg`

### macOS
`~/Library/Application\ Support/Steam/SteamApps/common/Counter-Strike\ Global\ Offensive/csgo/cfg/`

### Linux
`~/.steam/steam/SteamApps/common/Counter-Strike\ Global\ Offensive/csgo/cfg/`

## Launch params used
`-high -freq 144 -tickrate 128 -nod3d9ex -noforcemparms -noforcemspd -noforcemaccel -novid -nojoy -console +autoexec`

## Mouse
Install Mionix Naos 8200 software, currently 1.01. The current firmware is 1.28 at the time of upload. Load the profile into profile 1. For the love of fuck; do not add anymore profiles beyond profile 1. It borks the shitty NAOS software, remember?

- Mouse Settings:
    - Buttons as default
    - Polling Rate: 1000Hz
    - Double Click: 2
    - Scroll Speed: 4
    - Pointer Acceleration: Disabled

- Sensor Performance (X + Y the same):
    - Enable Refined Mode: Unchecked
    - DPI Settings:
        - 1: 400    Gaming
        - 2: 1200   Daily
        - 3: 2400   Gotta Go Fast
    - Pointer Speed: 1 (as this is overwritten by windows later on, set it to 1)
    - Lift Distance: 5

- Colour Settings:
    - Whatever

- Macro Settings:
    - None

Finally, as NAOS software alters windows sensitivity incorrectly, under Windows pointer options:

- Set the sensitivity to 6 out of 11 (starts at 1 on the left peg)
- Enhance pointer precision: Disabled

## Todo
- Split out config for easier management and centralise loading
