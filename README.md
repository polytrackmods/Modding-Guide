# Modding-Guide
This repo is like the build-your-own-x repo, except targeted at PolyTrack modding. You can learn both PML and ASAR modding basics, as well as examples/tutorials of different mods.

This repo is a work in progress

## Content:
Setup and Basics
- [Code Basics](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#code-basics)
- [Setting Up a Modding Environment](https://github.com/polytrackmods/Modding-Guide/blob/main/README.md#setting-up-a-modding-environment)
- [Setting Up a PML Repository](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#setting-up-a-pml-repository)
- [Exporting ASAR Mods](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#exporting-asar-mods)
- [PML Programming](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#pml-mixins)
- [Keybinds and Other Settings](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#creating-keybinds-and-other-settings)
- [Modding UI](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#ui-modding)
- [Sim Worker Basics](https://github.com/polytrackmods/Modding-Guide?tab=readme-ov-file#sim-worker-basics)

# Setup and Basics
## Code Basics
PolyTrack is programed in JavaScript however knowledge of HTML and CSS is also helpful when modding graphics. The game uses ammo.js for simulation, three.js for 3d graphics, and pako.js for track code compression, but for most mods you won't have to interact with these libraries. 

The code is split up into the main.bundle.js, which contains most of the games code, and the simulation.worker.js, which as the name suggests is a worker of the main bundle which handles the simulation. More recently, (0.5.1) there has also been an inclusion of an error handler script.

The code in the scripts is obfuscated - causing things like variable names to change from a helpful descriptive name (suspension_height) to random letters (rN) - which makes the code a lot harder to understand.
```
//Example:
const xy = class {
```

One common occurrence in code are private getters and private setters. These function set and get private variables within functions and classes. 
```
//Example:
//Setter (sets Pk)

Ay(this, Pk, document.createElement("div"), "f")

//Getter (gets Pk)

by(this, Pk, "f")
```

## Setting Up a Modding Environment

## Setting Up a PML Repository 

## Exporting ASAR Mods

## PML Programming and Mixins

## Creating Keybinds and Other Settings

## UI Modding

## Sim Worker Basics
