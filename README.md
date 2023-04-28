# Four-Fun
## Disk Collection of Four Player games for the MEGA65

![Four Fun Disk for the MEGA65](https://github.com/jim-64/Four-Fun/blob/main/image1disk.jpeg)

### This disk collection was put together for use with the MEGA65 four player joystick interface.

If there are other games that you think should be added, please contact me.
If there are games on this disk image that should not be shared like this, please ask and I will remove them.
64jim64 at gmail.com or Jim_64 on the MEGA65 Discord.

The disk image will autoboot if mounted to the default drive during power up. Otherwise, the command BOOT will start the disk once the disk is mounted. The boot sequence starts the MENU program.

### MENU PROGRAM
The MENU program allows for easy access to all the programs. Before loading the programs, it automatically reconfigures the computer for the proper mode (MEGA65 or GO64) and changes to any required video timing (PAL / NTSC).
Thanks to those that helped with my questions while getting the MENU functionality working. Special thanks to Kibo’s great C64RUN which is used to launch the “GO64” programs.
The Menu program is written is written in BASIC. It is driven by the SEQ file “MENU DATA”. You can modify it with the following commands:
EDIT ON
DLOAD ”MENU DATA”
LIST
Comments in the “MENU DATA” sequential file explain the format. Feel free to use this with other disk collections!

### ABOUT PROGRAM
The ABOUT program prints the “ABOUT DATA” sequential file to the screen. To edit its content:
EDIT ON
DLOAD ”ABOUT DATA”
LIST
Comments in the “ABOUT DATA” sequential file explain the format. Feel free to use this for any purpose!

### FOUR PLAYER TEST / DEMO PROGRAM
The 4 Player Test / Demo BASIC program allows you to easily test all four joysticks. Additionally, the code allows anyone to see how to read the four joystick inputs.


Enjoy! 
Jim_64
