# SteamDisk-For-Windows
Launch your digital Steam Library using legit 3.5 floppy disks
<img width="1773" height="887" alt="ChatGPT Image Jul 7, 2026, 02_14_01 PM" src="https://github.com/user-attachments/assets/a1e17062-f9b0-48a4-9203-287e003793f9" />

SteamDisk is a python/ps1 sctipt that you let run in the background of your linux build via a .sh/vb script to run Steam, Lutris, Native or Wine software after the insertion of a floppy disk inside a floppy disk drive

Yes, I am hopping on the "physical media" craze, and you should to!

This is an active PROTEST against Playstation and their shitty business model

BRING ME BACK MY DISKS, BRING THEM BACK RIGHT NOW—
____________________________________________________________________________________________________________
Features of SteamDisk include:
- Real floppy disk support
- Steam AppID launching
- Steam Shortcut Launching
- Wine Support
- Proton Support
- Lutris Slug Launching
- Swappable Media
- Native Linux Support
- Auto-Mounting of Floppy Disks
_______________________________________________________________________________________________________________
Supported Launchers
- Steam
- Steam Shortcuts
- Lutris
- Native Linux
- Wine
- Steam Proton
- Custom Commands
__________________________________________________________________________________________________________________
Your disk.ini files should include the following:

[SteamDisk]

Launcher=Steam

Game=Half-Life 2

AppID=220

Or alternatively, if you like adding mods, then add the shortcut ID for the Mod Launcher you use (usually hidden inside userdata->175504215->760->screenshots.vdf) to Lutris, and it'll launch after reading:

[SteamDisk]

Launcher=Lutris

Game=XCOM 2

Slug=xcom-aml (or whatever you call it)
__________________________________________________________________________________________________________________________________________________________________________________________________________________________
DISCLAIMER:

This is not an emulator, and I do not have ties to the company Valve or Steam. I simply want to bring physical media back to the forefront of gaming.

(Also Valve, if you're reading this, please steal my idea and make money off it, I will gladly pay you and you're the best company and I love you Gabe)
___________________________________________________________________________________________________________________________________________________________
This project has been tested on Linux, KDE Plasma, Bazzite
___________________________________________________________________________________________________________________________________________________________________
# Latest Features (as of v5)

**Physical Game Library**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Every floppy you own represents a game

Insert disk

Game Launches

Remove Disk

Close old game and swap it wih another floppy!

**Automatic Detection**
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
SteamDisk watches for floppies

No buttons or menus

No dealing with Linux not automounting correctly

It does it all for you, just insert the disk

**Disk.ini configuration**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Each disk will contain a .ini file

When you insert an empty floppy, it opens it up for you, and you make the .ini yourself or use the provided template

No scripting knowledge required bb!

**Linux Native**
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This is for Linux users, if you're Windows, just watch this video for a briefing on how this works on that: https://www.youtube.com/watch?v=zhoQRKMlCw4&t=419s

**Steam Runtime Detection**
-------------------------------------------------------------------------------------------------------------------------------------------------
SteamDisk imports Steam runtime enviroment variables before launching Proton applications, helping you improve compatibility with Proton games

**Crash Resilience**
-------------------------------------------------------------------------------------------------------------------------------------------------
It will no longer crash if an unexpected ejection of the disk is made

**Endless Runtime**
------------------------------------------------------------------------------------------------------------------------------------------------------
This bad boy will never cease to run

Reminding you that physical media is forever

And dumb Playstation GTA 6 codes will be a thing of the past

**AutoStart**
---------------------------------------------------------------------------------------------------------------------------------------------------------------
Set the .sh file as a launch script in your autostart settings

Upon restart, SteamDisk will be ready to go!
________________________________________________________________
Enjoy that giddy childhood sensation of game collecting!
