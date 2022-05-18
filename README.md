<img src="https://socialify.git.ci/dkdue/WindowsGSM.VRising/image?description=1&font=Inter&forks=1&issues=1&language=1&owner=1&pattern=Floating%20Cogs&pulls=1&stargazers=1&theme=Light" alt="Banner" width="768"/>

<p align="Center">
  <img alt="GitHub release (latest by date including pre-releases)" src="https://img.shields.io/github/v/release/dkdue/SteamCMD-Dedicated-Server?color=seagreen&include_prereleases">
  <img src="https://img.shields.io/badge/status-Beta-blue" />
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/dkdue/WindowsGSM.VRising?color=crimson">
  <img alt="Visitor Count" src="https://visitor-badge.glitch.me/badge?page_id=dkdue.WindowsGSM.VRising">
</p>



# The Game
https://store.steampowered.com/app/1604030/V_Rising/

# Important
*Your local save files are located within this area on your computer 

"%USERPROFILE%\AppData\LocalLow\Stunlock Studios\VRisingServer\Saves"

 However, just like with the settings, this can be overridden with the -persistentDataPath parameter.

# Configuring your V Rising Server
Now comes the fun part, setting up your V Rising game server to your liking.

To modify game server settings you can create two files

-ServerHostSettings.json

-ServerGameSettings.json

You can create these files in your VRisingServer\Settings folder

You can modify settings in here (in addition to the launch line) - these settings overwrite your launch line settings:

ServerHostSettings.json

{

"Name" : "My V Rising Server",

"Description" : "This is a role playing server",

"Port" : 27015,

"QueryPort" : 27016,

"MaxConnectedUsers" : 10,

"MaxConnectedAdmins" : 4,

"SaveName" : "world1",

"Password" : "SuperSecret",

"ListOnMasterServer" : true,

"AutoSaveCount" : 40,

"AutoSaveInterval" : 120,

"GameSettingsPreset" : "StandardPvP"

}

More info can be found here:

https://github.com/StunlockStudios/vrising-dedicated-server-instructions

# Installation
  1. Download the latest release
  2. Move VRising.cs folder to plugins folder
  3. Click [RELOAD PLUGINS] button or restart WindowsGSM

# License
This project is licensed under the MIT License - see the <a href="https://github.com/dkdue/WindowsGSM.VRising/blob/main/LICENSE">LICENSE.md</a> file for details
