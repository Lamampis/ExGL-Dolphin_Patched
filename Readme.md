## What is this fork?

Arch Linux users sometimes encounter the following issue when attempting to launch the AppImage:

```symbol lookup error: /usr/lib/libgio-2.0.so.0: undefined symbol: g_module_open_full```

This fork provides a patched AppImage that gets rid of the issue. 
You may also need to install ```libffi7``` from the AUR to get it to work.

Users have also reported that their controller's sometimes don't work, there is no fix for that yet as far as i know,
when a fix does emerge I'll be sure to include it here. 

The rest of the README is unchanged from the original.

## Project Introduction

This is a semi-custom build for Sonic Riders stuff, which includes the original Sonic Riders and Zero Gravity games, as well as the Sonic Riders DX and Zero Gravity: Regravitified mod projects.

**This repository is used to store the main ExGL Dolphin binaries and the semi-custom modifications done for the uses of the Riders community.**

For the actual source code and such, you can find them here:
https://github.com/BlueSwordM/Riders-Dolphin-EX

## What is it exactly?

This project takes the original Dolphin source code, modifies it to be more suitable to the needs of the Sonic Riders competitive community while adding our own changes, and builds it to be a neat little package.

This allows for better defaults for the Sonic Riders series of games(except for Free Riders), better netplay performance, special customizations, and general Quality of Life improvements.

## Where can I get people to play with and get support?

If you want to have fun amongst hundreds of players hungry for battle and get dedicated tech-support, you can join the ExGL Discord server. Without a doubt, the most active Sonic Riders community:

[Extreme Gear Labs Discord server](https://discord.gg/aRsAHcvVeN)

For more information on the mods themselves and to get a more detailed look at the Dolphin setup, you can find more information on the official ExGL website:
https://www.exgearlabs.com/home

This game also works just fine with Sonic Riders TE, so you can play with everyone from the Sonic community anyway.

The goal of this build is to unite everyone under a singular Dolphin build, so use it anywhere you like :)




