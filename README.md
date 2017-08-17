# i3-stuff
This repo contains all of my personal i3 config files and scripts I am using. Feel free to copy and adapt whatever you want.

## config
Contains the main i3 config file and the config file of i3blocks

## scripts
The following scripts are used in the config file:
- **audioctl**: a simple bash script for querying the current audio sink and volume
- **bg-set**: a smart wallpaper script. I have an own Github repo for this script. Check it out [here](https://github.com/thomasmauerer/SmartWallpaper)
- **lock**: a fancy lock script. I am using [this one](https://github.com/meskarune/i3lock-fancy)


The following scripts are not part of the config file but I use them nearly everyday. All of them make use of the *i3-msg* command in order to automatically start and move programs to the right workspaces and monitors.
- **setup**: a setup script for my laptop. It automatically sets the screen brightness, the audio sink and takes care of starting my main programs and moving them to the correct workspaces
- **worksetup**: a setup script for my working place. It takes care of correctly setting up my multi-monitor setup and audio sink, as well as starting and moving my main programs to the correct workspaces and monitors
- **homesetup**: a setup script for my home place where I only have one monitor. The rest is the same as in *worksetup*


### sidenote
You do not necessarily need to use the *i3-msg* command (like I do in the different setup scripts) in order to move programs to their desired workspaces. You could also directly assign programs to workspaces in the config file with the **assign** command. However, I do not want to bind my programs explicitely to workspaces (apart from Spotify) since sometimes I want to have all windows on the same workspace and I don't want to search for the stupid firefox popup on a different workspace.