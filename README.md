# MiSTer Core Audio Normalization

_**DISCLAIMER: Do not try this on your grandma's SD card. It may erase childhood pictures and save files.**_

## Background
* MiSTer's cores output wildly different levels of audio - these scripts aim to balance audio levels between cores
* I measured average and maximum SPL in dB, and recorded the core volume adjustment needed to achieve this level
* Each tick of OSD volume is roughly 6dB which is a factor of 2
* Measurements only include gameplay- some arcade cores sfx are still jarring
* Console core volume is the average of 3 games chosen semi-randomly (don't worry, I didn't pick terrible games like Castlevania, or Final Fantasy)
* This is not a perfect solution, but it's much better than going deaf

## Installation
* Copy these ciles to the "Scripts" folder of your MiSTer micro SD card
* (There are two versions of the script: 0dB (softer) and +6dB (louder))
  * The 0dB script brings all cores down to PCE levels (quietest console core)
  * If you use the +6dB script, set PCE's "Master" volume to "2X" to bump it up
* Run either script from MiSTer > Main menu > Scripts menu
  
## Roadmap
* Script to clear all core volume settings
* Computer cores to follow, please provide feedback :)
* Next step will be experimenting with audio filters, adjusting by smaller dB levels to fine tune things

Cheers!
