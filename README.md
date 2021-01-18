# MiSTer Core Audio Normalization

* MiSTer's cores output wildly different levels of audio
* I measured average and maximum SPL in dB, and recorded the core volume adjustment needed to achieve this level
* Each tick of OSD volume is roughly 6dB which is a factor of 2.
* Measurements ignore menu noises, instead focusing on gameplay (still some loud sfx in arcade cores)
* This is not a perfect solution, but it's much better than going deaf
* There are two versions of the script: 0dB (softer) and +6dB (louder). If you use the +6dB script, set PCE's "Master" volume to "2X" to bump it up.
** 0dB brings all cores down to PCE levels (most quite console core)
* More cores to follow, please provide feedback

* Next step will be experimenting with audio filters, adjusting by smaller dB levels to fine tune things.

Cheers!
