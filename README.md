# cod4-config
rose's cod4 config

## Installation
1. Download the CFGs
2. Place it in your "main" folder 
    `D:\Games\Activision\CoD4\main`
3. Edit the properties of your cod4 shortcut, and add these launch options to the end 
    `+exec _controls.cfg +set fs_game "mods/pml220"`
4. Open _controls.cfg and change whatever you like
5. Done! :D

## Explanation of Files
**_controls.cfg**
This is the config file with all my main controls in, filmtweaks, and well, literally all of my bindings.

### Jumping + Promod Switches
I prefer having two configs to switch between jumping + promod as it's a much cleaner way to set up a toggle between configs.
**_jump.cfg**
This is the config file for my binds specific to jumping, and has mainly fps binds associated to it.
**_promod.cfg**
Essentially the config file to reset controls that got changed by _jump.cfg ( I know I can re-exec _controls.cfg, but prefer a toggle ).

### Scope+Rifle Switches
Same reason I have seperate configs for jumping + promod. However I prefer to play on different Fields of view, and in order need a different sensitivity to compensate for the FoV change.
**_scope.cfg**
Sets FoV to 71.111, scale to 1.125, and sets my sensitivity to 0.668123.
**_rifle.cfg**
Sets FoV to 80, scale to 1.125, and sets my sensitivity to 0.67024746.

My sensitivity is so specific as I tried to get as close to 30cm/360 on 1600 dpi as I could.
