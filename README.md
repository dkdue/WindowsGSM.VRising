# WindowsGSM.VRising
🧩WindowsGSM plugin that provides VRising Dedicated server support!

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
