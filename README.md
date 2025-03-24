# CHIP-8 Emulator

This program aims to emulate a CHIP-8 virtual machine. It will be able to load CHIP-8 programs, interpret the instructions of the VM, generate graphics, and take in user input. ROMs for the emulator are not provided in this project.

## Controls

To run a rom that you have moved into the same folder, run: `./mychip8 myrom.ch8`

Controls are mapped in the interface to the keypad controls of the CHIP-8 in the following way:  
1 2 3 4  
q w e r  
a s d f  
z c v b

In the normal key layout, the controls are specified as they were on the COSMAC VIP system:  
1 2 3 C  
4 5 6 D  
7 8 9 E  
A 0 B F

An alternate key layout is provided for ROMs designed for the DREAM 6800 and ETI-660 computers if you come across any. In those systems, the control layout is this one that might seem more customary:  
0 1 2 3  
4 5 6 7  
8 9 A B  
C D E F

To use the alternate key layout, provide the `-k` flag to the program before the name of the rom to load.

To mute sounds, use the `-m` flag before the name of the rom to load.

## ROMs

To download a collection of CHIP-8 ROMs, use this [link](https://www.zophar.net/pdroms/chip8/chip-8-games-pack.html).
