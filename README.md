# Forge 1.18.2

## Forge Installation:

1.  Run Minecraft for the first time
2.  Open ***forge-1.18.2-40.2.1-installer.jar***
3.  The jar file will automatically find your Minecraft root directory
4.  Click on "Install Client" and wait for the libraries to install
5.  Open the Minecraft launcher and click on Installations, on the top left
6.  You will find an installation called ***forge***
7.  Hover over the installation and click on the button with the three dots on the right
8.  Click ***edit***
9.  You can rename the installation, but before you click ***Save***, do the following:

**For MacOS users:**
1.  On the Desktop, hold the option key and press on ***Go*** on the Menu Bar
2.  On the pop-down menu, click ***Library***
3.  Double click on ***/Application Support***
4.  Make a new folder called ***minecraft_forge_1.18.2***
> This method separates your modded directory from your vanilla/root folder, facillitating future uninstallation

**For Windows 10/11 users:**
1.  Hold ***WIN key + R***
2.  Type ***%appdata%*** and press Enter
3.  Make a new folder called ***minecraft_forge_1.18.2***

**Back on the Installations windows in the Minecraft Launcher:**
1.  On the ***GAME DIRECTORY*** header, click ***Browse*** on the right
2.	Select the folder you just created, called ***minecraft_forge_1.18.2***
3.	At the bottom of the window, click on ***MORE OPTIONS***
4.	In the ***JVM ARGUMENTS*** text box, you will find a sequence of argument that control many components of the Java Virtual Machine in which Minecraft runs
5.	Find the sequence of text that says ***-Xmx2G***
> This indicates the maximum amount of RAM allocated to the JVM.
6.	Only change the number within that string to half of your system's total memory.
    + If you have 4 GB of RAM, keep the string as ***-Xmx2G***
    + If you have 8 GB of RAM, change the string to ***-Xmx4G***
    + If you have 32 GB of RAM, change the string to ***-Xmx16G***	

> Note these are mere recommendations. If you know how much RAM is allocated to your system while it's idle,
you can add more RAM accordingly. For instance, if you're system uses 2 GB of RAM, and you have a total of 8 GB of memory,
you can push the limits even further, adding 6 GB of RAM instead of 4 GB. Keep in mind that if you run out of memory while playing,
the game will crash. This being said, large mod packs benefit from a larger RAM allocation.
7.  Click ***Save*** on the bottom of the page.

## Mods Installation

All mods are contained within a ***.jar*** file

1. Install mods within the forge root folder (***minecraft_forge_1.18.2***)
2. Paste all desired mod files inside the ***mods*** folder
3. Close Finder/File Explorer and run the forge installation

You should see on the bottom left the amount of mods installed
