# Admin-Pro
Version 1.22
Release date: 17:16 08/12/2005

## Change Log

Remember this is not a full change log. Sorry too much to list

### 1.22
- Fixed SH and BT jetpacks so they take off:)
- Forced players to use pistol before entering plane, This solved sniper issues
- Fixed missing ambient sounds
- Fixed parachute bug

### 1.21
- Fixed jetpack bug, sometimes you would spawn with 2 jetpacks.

### 1.20
- removed team count code from team balance and added to nagle.scr for globality
- added radio drop feature to countdown
- updated some code,
- updated _fps fix to protect other servers and fix typo in disconnect:D
- players with radio cannot fly planes now
- players with jetpack can not pickup radio
- fixed error reports in under map
- animation for parachutes in BT and SH
- added jetpack mod
- fixed BT survivor error
- Added medic bar for SH and BT
- Changed Hud draw element Index for messages to fix conflict with Freeze Tag
- Added player jetpack command

### 1.12 beta
- Fixed game.reset not keeping mod on/off settings.
- Added extra setting to game.reset to allow keeping mod on/off settings but map specific.
- game.show_on_mods Now shows 1 second after map change and round.

### 1.11 beta
- When turning on scripts in console settings properly loaded. 
- Removed counter from anti camper ( if needed can be anabled still, contact me)
- Removed 'Camper Mod On' and 'Camper Mod OFF'.
- Added optional mod on off info on round start for all players. Also informs mod on or off when changed in console ( game.show_on_mods = 1 added to advanced.txt )
- Ambient script from BT used. Should stop missing ambient sounds on BT and SH.
- added command "light" light a player, "light off" for light off
- Message center colour "random" added
- Message center supports colour's in float
- Message center supports individual message colours
- Added more functions to strings.scr
- Planes are not detected as "under the map"

### 1.0 beta
The change log is too big so I will just list the main things sumerised. A full change log can be found on http://elgan.funmodsforu.com/ 

- Re- Scripted the main settings and mods loading. 
- Re-scripted mines. Added extra features to them like gun specific disarm and choice over which mines run.
- Changed Mods.txt to load only settings needed. Extra settings are loaded in real time if needed
- After restart command is used mods turned on or off stay on or off. Settings are kept correctly over map change.
- Added new commands.
- Re-scripted all punishment commands and optimised them.
- Dead players on duration spot will no longer burn if they do not respawn.
- Map specific changed to remove the dm/, obj/, or /lib prefix. Single player maps will still work.
- MG42 team swap fix optimised
- Fixed various reported and non reported bugs.
- Optimised console help system and added extra information.
- Fixed and added to message center.
- Weapons limiter optimised. 
- Added skin fix by sorridstorker for BT.
- New bugnade fix from HAL.
- New mods and gametypes.
- Survivor and countdown get extra features.
- Flyable planes eject different to stop jumping under the map.
- Whole mod runs faster and is more likely to run over other mods using state files.

## Description
	
The mohaa series most advanced server side mod. It contains many server bugs and exploit fixes 
making it a must download. It also contains many extra mods and possibilities.
With this mod admins have more control over players and the mods running. 
Everything is easily editable via simple text files giving the ability to change mods to how
you want them or to setup different mods differently on different maps or just run different mods.

## Possible Conflicts

Mods that use state files or depend on state files are likely to stop functioning correctly. These include mods like weapons limiters.

Cvars

Admin_cmd

This ( admin_cmd ) cvar is the main cvar. The mod uses only one cvar for doing everything!

This cvar can be used to punish/admin players, change settings, change mods, run or stop mods while the server is running without needing to stop and edit the settings files.

## How to install ?

Place the Admin-Pro_1.20.pk3 inside your maintt/mainta/main folder.
Place the settings folder in your maintt/mainta/main folder.

If you can not upload a folder to a remote server. Make a new pk3 using either a zip file utility
like winrar. Optionaly you can donwload and use pakscape. Use the extension .pk3 with both. 
For more infomation on creating a settings.pk3 contact me.

#Contact me

#Email : elgan.sayer@gmail.com

Ask in the forums:

	www.mods-r-us.net

	
## Credits

Thank you to everyone who helped test and reported bugs.

Thank you to:

@(...:.:...)@ , Hal for the bugnade fix
Sorridstoker for the skin fix
mefy for the place location script and under map detection script
jv_map Jeroen Vrijkorte for little tricks , info and answering questions about vectors over and over.
rindog for his initial punishment scripts

Forgive me if i missed anyone :)

