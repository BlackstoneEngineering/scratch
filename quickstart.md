# Getting Started with mbed OS
To use mbed OS you develop online using the **online compiler** or offline using **mbed CLI**. Both support Git and Mercurial repositories, which makes it easy to switch from online to offline development whenever you want.
Below there are two options for getting started, Online or Offline. Please choose one and follow along. Make sure to get all the way through so you are properly oriented within the ecosystem. 

## Online Environment
The mbed online compiler is the best way to get started with mbed, it requires no setup or advanced knowledge of embedded systems to get started. 

### Install Environment
1. Create an [mbed account](http://developer.mbed.org/signup)

### Setup Environment
1. Open 'mbed.html' file on your board 
  - If you do not have a board go to developer.mbed.org/platforms, select a board, click 'Add to Compiler'
1. [Import Blinky program](mbed import teams/mbed/blinky) - make sure to update all libraries to their latest version at import time


### Build your first program
To build your first program click on the `Compile` button, this will trigger a compilation on our backend. When finished the compiler will prompt you to download your compiled program. You can either save this file directly to the mbed board or first save the binary to your computer and then copy it to your mbed board.

You should now see the LED on your board blinking. If you do not try resetting the device. 

### Modify
Now lets try modifying your program. Try changing the speed of the LED by changing the wait time in the main.cpp file. Once you have changed the program recompile, download, and copy to your board. 

### Debug
The Online Compiler cannot directly do debugging, so you have two options.
1. Export the program to an offline IDE like Keil, IAR, or Eclipse. To do this right click on your program, click export, select your IDE and hit go. You will be asked to save a zip file with all the files. 
1. To do basic debugging is to use the `printf` commands in your code and read them using a serial terminal like [CoolTerm](TODO) or [Putty](TODO). 

TODO: Instructions on how to use putty

### Reccomended Resources
Congratulations on building your first program with mbed OS! Below are some resources for continuing development.
- mbed OS API
- Advanced Debugging with mbed
- mbed Enabled - creatin an mbed platform
- mbed HDK - eagle libraries for creating mbed platforms
- ARM mbed youtube channel - 
- .... TODO: anything else that doesnt fit on api / tutorial section

## Offline Environment
mbed CLI is the best way to develop with mbed offline. mbed CLI is the same tool we use on the backend for the online compiler, wrapped up nicely in python bindings and delivered for you to use offline, on a plane, on a train, behind a firewall, or anywhere else you may want to develop. 

### Install Environment
To use mbed CLI you wil need the following programs installed on your computer
1. [Python 2.7.9+](TODO)
2. Compiler of your choice: [GCC](TODO), ARMCC, or IAR
3. Run `pip install mbed-cli` from your command line

### Setup Environment
1. Make sure the compiler is available in your global path.
  * GCC - run `arm-none-eabi-gcc --version` in your terminal.
  * IAR - run `iar --version` TODO
  * Keil - run `uvision` TODO

2. .....TODO

### Build your first program
To import your first program run `mbed import blinky`. This will pull down the source for mbed OS, the source for the blinky program, and any libraries included in the progam. In this case we are pulling down the source from <TODO- link to code>. Using this method we could import any program using `mbed import URL` where we replace URL with the git or mercurial address of our code. 

The next thing you will want to do is set your toolchain and the target you are compliling against. To do this we will use two commands, the first is `mbed target auto`, this will 'auto' detect the board plugged into your computer and compile for it. The second command is `mbed toolchain X` where you replace `X` with the toolchain your are using. For example, to compile using GCC you would use `mbed toochain GCC_ARM`. For a full list of supported compilers use `mbed toolchain --supported`. 

Finally, compiler your program using `mbed compile`. If there are any failures and you want more information use `mbed compile -vv` for verbose output. The compiled binary will be in `/BUILDS/TARGET/ProgramName.bin`. Copy / paste this file to your device and the board will program itself.

You should now see the LED on your board blinking. If you do not try resetting the device. 

### Modify
Now that you have made the LED blink try changing the the speed of the LED. Open up the main.cpp file and making your changes. To test your changes you will need to recompile your code again using the `mbed compile` command and copying the binary to the board. 


### Debug
There are many ways to debug a board. If you are using Keil, IAR, or Eclipse you can use the `mbed export` command to generate project files. Another way to do basic debugging is to use the `printf` commands in your code and read them using a serial terminal like [CoolTerm](TODO) or [Putty](TODO). 

TODO: Instructions on how to use putty

### Reccomended Resources
Congratulations on building your first program with mbed OS! Below are some resources for continuing development.
- mbed OS API
- Advanced Debugging with mbed
- mbed Enabled - creatin an mbed platform
- mbed HDK - eagle libraries for creating mbed platforms
- ARM mbed youtube channel - 
- .... TODO: anything else that doesnt fit on api / tutorial section
