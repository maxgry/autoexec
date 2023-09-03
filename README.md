# maxgry's CS:GO autoexec

Mouse and Keyboard binds: 
![Keybinds](https://raw.githubusercontent.com/maxgry/autoexec/main/csgo_keys.png)
(very fine)

## Setup

1.  Set Launchoptions

     Set them under `Steam -> Library -> Right-Click CSGO -> Properties -> General -> LAUNCH OPTIONS`

     My Launchoptions:

     `-console +exec autoexec -novid -tickrate 128 -noborder -windowed -language english -threads 4 -refresh 144 -nod3d9ex1`

2.  Place the autoexec

    Place the `autoexec.cfg` file into 
    - `<Path to Steam>/steamapps/common/Counter-Strike Global Offensive/csgo/cfg/` or
    - `<Path to Steam>/userdata/<Your Steam AccountID>/730/local/cfg/`

    whereas `<Path to Steam>` depends on your OS and used directory
    - Windwos default: `C:\Program Files (x86)\Steam\`
    - SteamDeck default: `/home/deck/.steam/steam/`
    - SteamDeck SD default (/steamapps): `/run/media/mmcblk0p1/steamapps/`
    - Debian default: `/home/maxgry/.local/share/Steam/`
  
    and `<Your Steam AccountID>` is your Steam AccountID as found in your Trade URL:

    `Steam -> Profile -> Inventory -> Trade Offers -> Who can send me Trade Offers? -> https://steamcommunity.com/tradeoffer/new/?partner=<Your Steam AccountID>&token=yomoma`

     `wget https://raw.githubusercontent.com/maxgry/autoexec/main/autoexec.cfg`

> [!WARNING]
> lul
