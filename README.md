# Modding-Guide
This repo is like the build-your-own-x repo, except targeted at PolyTrack modding. You can learn both PML and ASAR modding basics, as well as examples/tutorials of different mods.

This repo is a work in progress

## Content:
[Setting Up a Modding Environment](https://github.com/polytrackmods/Modding-Guide/blob/main/README.md#setting-up-a-modding-environment)

# Setup and Basics
## Code Basics
PolyTrack is programed in JavaScript however knowledge of HTML and CSS is also helpful when modding graphics. The game uses ammo.js for simulation, three.js for 3d graphics, and pako.js for track code compression, but for most mods you won't have to interact with these libraries. The code is split up into the main.bundle.js, which contains most of the games code, and the simulation.worker.js, which as the name suggests is a worker of the main bundle which handles the simulation. More recently, (0.5.1) there has also been an inclusion of an error handler script.

## Setting Up a Modding Environment

## 
