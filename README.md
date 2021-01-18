# MiSTer Core Audio Normalization

_**DISCLAIMER: Do not try this on your grandma's SD card. It may erase childhood pictures and save files.**_

* MiSTer's cores output wildly different levels of audio - these scripts aim to balance audio levels between cores
* I measured average and maximum SPL in dB, and recorded the core volume adjustment needed to achieve this level
* Each tick of OSD volume is roughly 6dB which is a factor of 2.
* Measurements ignore menu noises, instead focusing on gameplay (still some loud sfx in arcade cores)
* This is not a perfect solution, but it's much better than going deaf
* There are two versions of the script: 0dB (softer) and +6dB (louder)
 * If you use the +6dB script, set PCE's "Master" volume to "2X" to bump it up.
 * The 0dB script brings all cores down to PCE levels (quietest console core)
* Computer cores to follow, please provide feedback :)

* Next step will be experimenting with audio filters, adjusting by smaller dB levels to fine tune things.

Cheers!
