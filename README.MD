# How to Fix Quartus Scaling Issue for High Resolution Screens

**This script assumes a 1440p or 4K resolution with a desire of 225% scaling (I found this to be ideal).**

## Installation Instructions
1. Clone the repo (or download to a .zip and extract).
2. Copy `qmegawizq.exe.manifest` and `quartus.exe.manifest` to the Quartus `/bin64` folder. For Quartus Lite 17.1, this directory is `C:\intelFPGA_lite\17.1\quartus\bin64`
3. Add `Add-PreferExternalManifest-to_reg.reg` to your Windows Registry. To do this, double click the file or follow [these instructions](http://www.tomsitpro.com/articles/windows-10-registry,2-1015.html).

## Before
![Before](https://i.imgur.com/1sEWyKl.png)

## After
![After](https://i.imgur.com/nnRGpQ8.png)
