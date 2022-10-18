# pram0d's Analogue Pocket OpenFPGA Cores

This repo contains the distribution files for all my Analogue Pocket Cores. 

**NOTE: THIS REPO CONTAINS NO ROM OR GAME FILES. NO LINKS OR PRE-ASSEMBLED ROMS WILL BE PROVIDED TO YOU BY ME IN ANY CAPACITY. PLEASE ENSURE YOU HAVE THE LEGAL AUTHORITY TO PLAY THESE GAMES IN YOUR JURISDICTION.**

Basically, you will need to do the following to install the cores on your pocket (Windows):

1) Place your rom ZIP files in a directory on your computer and take note of the path.
2) Open a command prompt, and go to the directory `/tools`. ie. `cd tools`.
3) Execute the batch file script provided, replacing the path to your rom files: ie. `assemble.bat C:\Users\username\Desktop\rom`. The script will utilize the MRAs in the mra directory of the repo, and place the assembled rom files in the proper directory locations in `dist`.
4) Copy everything **inside** `dist` to your SD Card for the Pocket. ie. `Assets`, `Cores`, `Platforms`.