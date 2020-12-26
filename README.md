# Scripts

This repository contains all of the scripts required to create an ameliorated Windows 10.

These scripts are used in conjunction with each other to, in part, create an Ameliorated Windows 10 install from scratch. These are divided into two folders, one for Windows and one for Linux. They have been divided into BASH and BATCH for simplicity's sake. The reason for not dividing them into Windows and Linux is due to the rational that some of the scripts, while they are BASH scripts, they are made to be run on Windows. The reason for this is made apparent in the documentation.

## Download

If you are following the [documentation](https://wiki.ameliorated.info/doku.php?id=documentation_2004), simply download the latest [release](https://git.ameliorated.info/malte/scripts/releases) for the version of Windows 10 you are using.

## How to use these scripts

The documentation for the use of these scripts is on the wiki, [found here](https://wiki.ameliorated.info), to avoid any unnecessary problems, please follow this documentation when using these scripts. Simply put, the batch script is to be run both before and after the bash script, and the bash script *must* be run in Linux.

### Batch scripts

The main script in the folder is the "amelioration" script, this is the script that sets up everything that can be set up in Windows itself. This script is used both before and after the BASH script is run in Linux.

### Bash scripts

This folder holds both the main "ameliorate" script and auxiliary scripts. The auxiliary scripts are helpful in setting up Windows and can be ran in Windows with Cygwin. As with all BASH scripts, the file permissions may be need to be changed so that they can be executed, example below.

`chmod +x ameliorated_2004.sh`

## FAQ

 **1. Which versions of Windows do these scripts worth with?**  
    Ans: The scripts are made to work with a specific version of Windows 10. Use on any other version may result in unexpected behavior or a broken system.

# Credits
The original authors of these scripts are the awesome guys over at [Ameliorated](https://ameliorated.info). 