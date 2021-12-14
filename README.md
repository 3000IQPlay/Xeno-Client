![xenotheme](https://cdn.discordapp.com/attachments/901443220389646369/917855640704143380/text-1638904225098.png)

[![GitHub All Releases](https://img.shields.io/github/downloads/XenoClientDevelopment/Xeno-Client/total.svg)](https://github.com/XenoClientDevelopment/Xeno-Client/releases/)

A Minecraft Forge 1.12.2 Utility Mod intended for Anarchy Servers. 
This client is currently weak in it's PVP modules, but hopefully makes up for that in render modules. 
I would use this as a secondary client, and use it especially for its render modules.
It is currently the only client I (Wolfsurge) could find with an Outline StorageESP, apart from Future (and my old client).
It's fairly new, so the download counter is low (but it is safe!)

## Installation
Download the pre-compiled jar from the releases tab. It is safe, but if you don't trust us, just don't use the client. The dev team was arguing about whether
to keep it closed source or not, and so the source is private.

## Usage:
<details>
  <summary>Click to expand!</summary>  
 - Download the .jar file from releases
 - Put the .jar in your mods folder by pressing Windows + R and typing in %appdata% open the .minecraft/mods folder.  
 - Press RSHIFT to open the ClickGUI
</details>        

## Credits:
Client Devs: Wolfsurge / Mathew101Q / q3m

Project starters: Fyre - SoldierMC
  
Texture Pack Editor: Fyre 
  
Beta Tester/Helpers: HAV0X - SoldierMC - IdentifyDelay - NGILDQS - Fyre - Mathew101Q - Wolfsurge - q3m
  
"Some modules are partially skidded, but not fully. We plan to remove this soon"

## Discord:
If you need help with anything in the client, click [here](https://discord.gg/YPeVBdZMQA) to join the discord.

## Latest Release Notes

<details>
    <summary>Click to expand!</summary>

## Modules Added
<details>
  <summary>Click to expand!</summary>

    IceSpeed
    - Lets you control the ice slipperiness, with one setting (speed)

    MobOwner
    - Lets you see who owns tamed entities

    AutoCrystal
	- Places and breaks End Crystals for you. Lots of settings, works decently.

    NoPush
	- Stops entities pushing you around.
    
    FakePlayer
    - Spawns a client-side fake player, useful for configurating combat modules.

    CameraClip
    - Lets your third-person camera clip through blocks.

    HoleFill
    - Fills holes around enemy players. Works okay.

    ShulkerPreview
    - Shows the contents of shulker boxes in your inventory.

	FastXP
	- Throws XP bottles fast.

    AutoXP
	- Automatically repairs armour with XP bottles.
    
</details>

## Modules Updated
<details>
  <summary>Click to expand!</summary>
  
    Sprint
	- Added a mode setting with two modes - Legit and Omni

	Velocity
	- Added five settings: Velocity PKT, Horizontal, Vertical, Explosion, and Fishhook
  
    ElytraFly
	- Added a Activate Key setting. Press this to toggle the elytra flying state when in midair.

    ArrayList
	- No longer a draggable HUD module, instead open the settings to change its position.
    
    Offhand
    - Added more settings, such as TotemSwap.

    HoleESP
    - Added a new mode, and fixed a bug.
</details>

## Other Changes / Bug Fixes
<details>
  <summary>Click to expand!</summary>

    GUI
	- Fixed a weird bug when opening buttons (they move up)
	- Added a CButtonOutline option, when the buttons are closed, it still displays an outline around them.
	- Fixed a bug where the module buttons would spasm when trying to move further than they were meant to.

	HUD
	- Added a blur option to the HUD config screen. Access from the 'HUD' module.
    - Improved ArrayList

</details>
</details>

## ClickGUI
The GUI has 3 themes. Xeno (default), Plain, and Future. This can be changed through the ClickGUI module's settings.
![xenotheme](https://github.com/XenoClientDevelopment/Xeno-Resources/blob/main/xenotheme.png?raw=true)

## Features
<details>
  <summary>Click to expand!</summary>

  - Scrollable ClickGUI
  - 28 Modules
  - 10 HUD Modules
  - 5 commands
  - 3 GUI Themes
  - Custom Main Menu
</details>

## Modules
<details>
  <summary>Click to expand!</summary>
  
  # Combat
  - Aura                  (Quite a few settings, probably powerful with a good config?)
  - AutoArmour            (Has a delay setting, but isn't that good)
  - Blink                 (It works.)
  - Offhand               (5 modes, Totem, Gapple, Crystal, Pearl, Chorus)
  - Surround              (awful, use a different client)   
  - AutoCrystal		  (OK, alright with a good config)
  - HoleFill		  (Meh. It works.)
  - FastXP		  (Works.)
  - AutoXP		  (Should work fine.)	
	
  # Movement   
  - ElytraFly             (Should work on most servers.)
  - Fly                   (Only the vanilla fly, will most likely get you kicked, use NoFall with it)
  - Jetpack               (Will probably get you kicked)
  - NoFall                (Should work)
  - Reverse Step          (It works.)
  - Sprint                (Good.)
  - Step                  (Works on servers that allow step.)
  - Velocity              (It works.)
  - IceSpeed 		  (Decent.)
  - NoPush 		  (Works well.)
  
  # Render   
  - Chams                 (Decent)
  - ESP                   (3 modes - Outline, Box, and Glow & has outline Item ESP)
  - Fullbright            (Good, two modes - Gamma and Effect)
  - Hole ESP              (A bunch of settings)
  - Item Physics          (Good)
  - Nametags              (Good)
  - No Render             (Quite a few settings.)
  - Storage ESP           (2 modes - Outline and Box)
  - Tracers               (Good)
  - MobOwner 		  (Works, has a custom font option.)
  - CameraClip		  (Works)
  - ShulkerPreview 	  (Looks good and works properly.)
	
  # Player   
  - Fast Break            (Works)
  - Fast Place            (Works)
  - Anti AFK              (Works)
  
  # Misc
  - AutoEZ                (Customize message in the settings)
  - MCF                   (Middle Click Friend, works)
  - Suffix                (Customize message in the settings)
  - FakePlayer		  (Works)
	
  # HUD
  - Armour
  - Array List
  - Client Name / Watermark
  - Coordinates
  - FPS
  - Inventory
  - Ping
  - Totems
  - TPS
  - Welcomer
  
</details>

## Commands
<details>
  <summary>Click to expand!</summary>
  
  Format - [name] [syntax] [description]
  
  * Bind [bind <set|clear> <module> <key>] [Bind module keybinds to keys]
  * Elytra [elytra key <key>] [Set the keybind for toggling the elytra flying state]
  * Friend [friend list | <add | remove> <playername>] [Friend players, to stop Aura attacking them ETC]
  * Gui [gui reset] [Reset the ClickGUI]
  * Help [help] [Shows help!] 
</details>
  

