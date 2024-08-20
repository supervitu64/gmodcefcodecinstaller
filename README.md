# Garry's Mod CEF Codec Fix installer
i made this quick and dirty installer for Solstice's glorious CEF codec fix, that basically solves a bunch of problems Chromium and game related.

## MAKE SURE TO HAVE THE "x86-64 - Chromium + 64-bit binaries" BETA ENABLED, ELSE IT WILL NOT WORK!!

original work by Solstice: https://github.com/solsticegamestudios/GModCEFCodecFix


copy paste the following line to your terminal (make sure that wget is installed):

```wget https://github.com/supervitu64/gmodcefcodecinstaller/releases/download/tag/install-cefcodecgmod.sh && sudo chmod +x install-cefcodecgmod.sh && ./install-cefcodecgmod.sh && rm -rf install-cefcodecgmod.sh && rm -rf GModCEFCodecFix-Linux.1```

the script will automatically download the installer, give it execution permissions, execute it, then delete itself and the CEF installer. depending on your internet speed (or if another program is downloading something) the CEF script may take a while to download. the patching speed may be affected by your target drive's speed (for example it may take an excruciating eternity if it's an HDD).
