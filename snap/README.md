# Unofficial Snap Packaging for Open Syobon Action (オープンしょぼんのアクション)
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![(Placeholder) Icon of Open Syobon Action (オープンしょぼんのアクション)](gui/open-syobon-action.png "(Placeholder) Icon of Open Syobon Action (オープンしょぼんのアクション)")

**This is the unofficial snap for [Open Syobon Action (オープンしょぼんのアクション)](https://github.com/angelXwind/OpenSyobonAction)**, *"An open-source cross-platform port of the unforgiving Japanese platformer"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `open-syobon-action` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/OpenSyobonAction-snap.svg "Build Status of the `open-syobon-action` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/OpenSyobonAction-snap)

![Screenshot of the Snapped Application](local/screenshots/title-screen.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install open-syobon-action
    
    # Connect the snap to optional security confinement interfaces #
    ## Allow the game to access your joysticks ##
    sudo snap connect open-syobon-action:joystick
    
    # Launch the game #
    open-syobon-action
    snap run open-syobon-action # If you have another existing installation

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/open-syobon-action)

## What is Working
* Launch game
* Sound
* Move
* Jump
* Killed by numerous stuffs
* Switch levels from title screen
* Self-destruction
* Mystery Dungeon
* Reconsider life choices
* Level 1~3 playthrough

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/OpenSyobonAction-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/OpenSyobonAction-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
