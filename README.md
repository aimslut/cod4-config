# cod4-config
charlie's cod4 config

## Installation
1. Download the CFGs
2. Place it in your "main" folder 
    `D:\Games\Activision\CoD4\main`
3. Edit the properties of your cod4 shortcut, and add these launch options to the end 
    `+exec _controls.cfg +set fs_game "mods/pml220"`
4. Open _controls.cfg and change whatever you like
5. Done! :D

## What RawOn and RawOff are for
For some reason in Windows 10, there appears to be input delay and mouse acceleration in quake engine games.
So I use Raw-Input using `cl_bypassMouseInput`, which sends the mouse input directly to the engine, but it isn't picked up by the UI for some reason.
This is where seperate configs come in handy; as you can set it to turn off at launch, but also turn off when you hit the Escape key (for pausing), and also "O".
