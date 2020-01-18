# Kazuya's CS:GO Settings
This is my current Counter Strike: Global Offensive autoexec config. Feel free to use this configuration as a template for your own gameplay!

### What's this?

The goal is to provide an easy and fast way to get personalized CS:GO configurations in place to have a more tailored gaming experience.

Normally, you would configure your CS:GO game using the GUI.
The changes are then saved to the `config.cfg` file or `video.txt` and `videodefaults.txt`.

This repository provides `autoexec.cfg`, which will automatically configure in-game settings upon launch. This is crucial for professional and semi-pro players who travel often to tournaments and need to frequently set up their personalized settings on tournament computers.

### How to use
Put *autoexec.cfg* in `...\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`.

### How it works
CS:GO automatically executes *config.cfg* on startup. *config.cfg* executes *autoexec.cfg*, which then executes all the personalized configs.
If this doesn't work, try putting `exec autoexec.cfg` in your config.cfg file, or `+exec autoexec in your launch options`. Typing `exec autoxec` into the in-game console will also work.

### Launch Options

	-novid -nojoy -d3d9ex -high -threads 8 -tickrate 128 -console

Enter launch options at `Steam > Library > Counter-Strike: Global Offensive (right-click) > Properties > Set Launch Options...`

### Other Settings
+ Windows Sensitivity: 6/11  
+ Enhance Pointer Precision: No  
+ Mouse DPI: 400  
+ Mouse Polling Rate: 1000hz  
+ Nvidia VSync: Off
+ Nvidia Maximum Pre-Rendered Frames: 1  
+ CS:GO Resolution: 1280x960 stretched
+ Nvidia Freestyle: HDR Toning 100  
+ [Simple Radar](http://simpleradar.com/)
