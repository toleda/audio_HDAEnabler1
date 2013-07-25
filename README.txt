audio_HDAEnabler1
============
OS X Realtek ALC885 through ALC898 Onboard Audio

HDAEnabler1.kext installed with a Realtek AppleHDA.kext enables OS X Realtek ALC onboard audio on Intel based motherboards with a bootable clean install of OS X. HDAEnabler1.kext injects Audio_ID = 1 for non-DSDT systems.

In ML, The audio_HDAEnabler1.kext supports 
1. Audio_ID: 1 for 3 (no 5.1), 5 and 6 port Realtek ALC onboard audio
2. Realtek audio codecs: ALC885, ALC887, ALC888, ALC889, ALC892, ALC898

Download
1. https://github.com/toleda/audio_HDAEnabler1
2. Select: Download ZIP

Installation
Install HDAEnabler1.kext with Terminal, DPCIManager, Kext Wizard, etc.

Troubleshooting
1. ML-Realtek ALC AppleHDA Capabilities.pdf https://github.com/toleda/audio_ALCInjection

Credit
Kabyl

toleda
https://github.com/toleda/audio_HDAEnabler1
HDAEnabler1.kext.zip
README.txt