<div align="center">

# 🎮 Game Specific Patches & DLL Wrappers  

***created and maintained by***

[![Chip-Biscuit Website](https://img.shields.io/badge/Chip--Biscuit-Website-blue?style=for-the-badge)](https://chip-biscuit.github.io/)

Reverse Engineering • Programming • Patching • Game Improvements • DLL Creation 

[![Total Downloads](https://img.shields.io/github/downloads/Chip-Biscuit/Lego-Star-Wars-2005-PC-Resolution-AspectRatio-HUD-FIX/total?style=flat-square)](https://github.com/Chip-Biscuit/Lego-Star-Wars-2005-PC-Resolution-AspectRatio-HUD-FIX/releases)



<sub>click the Total Downloads button above to take you to the releases page and download the zip at the bottom</sub>

</div>


# Lego Star Wars (2005)

# Resolution Fix

![ezgif com-animated-gif-maker (5)](https://github.com/user-attachments/assets/ebb5e448-56aa-4671-b8cc-c4263f29c29b)

# Debug/ Developer Menu Enabled

![ezgif com-animated-gif-maker (6)](https://github.com/user-attachments/assets/3f8713c7-bbb7-407a-91d0-42c61be9cc79)


# Requirements before using fix
Before using the fix for it to work properly you must have patched the game up to 1.0.0.2 release. If you have not updated your Lego Star Wars (2005) already then you can download the patch from here - https://community.pcgamingwiki.com/files/file/438-lego-star-wars-patcher/ 

# Instructions
Go to releases and download the latest LegoStarWars(2005)Fix.zip, extract the d3d9.dll and d3d9.ini files into your game folder next to the LegoStarWars.exe file and you are good to go! You can edit the settings you wish to use in the d3d9.ini file.

# Resolution/Aspect Ratio
The default for resolution is set to (1920 x 1080) in the d3d9.ini file. Put the resolution that you wish to use in both the Width and Height area.
Aspect Ratio and Hud size is auto calculated by the Resolution you choose.

# FPS
The default for FPS is (60) you can change it as you wish with the FPSLimit option in the d3d9.ini file. It is recommended to not go above 60.

# Debug Menu

Put ChipDebugLSW.exe and ChipDebug.ini with d3d9.dll and d3d9.ini 

go into ChipDebug.ini and set the settings, you should pay attention to your region of your game. if you want the game to run after you run the patcher program set LAUNCH_GAME=1 if not then LAUNCH_GAME=0 default is 0 


 REGION SETTINGS:

    Set EXACTLY ONE of the following to 1.
    All others must be 0.

    EU        = Patch the EUROPE / PAL version of the game
    EU_RESET  = Restore the ORIGINAL EU executable

    US        = Patch the UNITED STATES / NTSC version of the game
    US_RESET  = Restore the ORIGINAL US executable

  Examples:

    Enable EU debug:
      EU=1

    Disable EU debug:
      EU_RESET=1


[REGION]

Region selection (choose ONE only):

    EU=1
    EU_RESET=0
    US=0
    US_RESET=0

Debug menu becomes available in the game after patching it 
once enabled, advice don't use in the main menu its a bit buggy
use it once you get into the game itself by pausing and going to options.

After setting up in the ini then run ChipDebugLSW.exe then you can play the game normally by using LegoStarwars.exe, if for any reason you want to turn off developer mode then just use the patcher program again. it will also give you a LegoStarwars.exe.bak incase of failures.

# Vote to see the game return via GOG Dreamlist
If you are interested in potentially seeing this game easily available to purchase and use today then go and vote on the games GOG Dreamlist to help make this become a reality, you can vote for the game here and write a message about the game if you wish – https://www.gog.com/dreamlist/game/lego-star-wars-the-video-game-2005 

# Issues/Problems
If you have any issues, with the fixes then please go to discord for help linked below. https://discord.gg/eVJ7sQH7Cc
Credits
Credit to Elisha Riedlinger for the base wrapper and ThirteenAG.

### Fix Enhancers  
https://fixenhancers.wixsite.com/fix-enhancers

“Creating compatibility fixes and enhancements for legacy PC games.”

# Chip
- founder
- reverse engineer
- programmer
- developer
- Game Preservationist
  
<img width="250" height="500" alt="my logoo" src="https://github.com/user-attachments/assets/9bb13d3f-0734-4f1d-b68f-14114b13744a" />


# JokerAlex21 
- founder
- admin
- tester 

<img width="250" height="250" alt="YouTube_Logo" src="https://github.com/user-attachments/assets/5c7204ca-4bca-4673-8117-965732e7ee6d" />

