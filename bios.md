# BIOS / INTER-SETUP

## This will be shorter since there's less to say about the BIOS but congrats for making it through the hardware rant, more of that to come...


Why did I call this INTER-SETUP, because it's after the PRE-SETUP and before the POST-SETUP, deal with it.



## The BIOS is quite complex and A LOT for me to go over, so I'll link to a lot of guides and explain how to follow them.


BEFORE YOU DO ANYTHING IN THE BIOS!!! make sure you know what a CMOS battery is and how to reset it, good motherboards have a button to reset it without taking apart your computer.

You can do manual settings in the BIOS but some will always be hidden, to unhide these we use special programs like GRUB and SCEWIN, most of the guides I'll link will be SCEWIN as that's the program I work in.

For manual settings, keep this in mind, turn OFF everything:

- power saving
- spread spectrum, spectrum 
- dynamic stuff like cores and voltages
- E cores on Intel and second CCD on multi-CCD AMD processors
- hyperthreading or SMT
- VT-D, and or ANY virtualization like IOMMU on AMD
- C-states and anything related to it
- Speedstep and speedshift, anything related to dynamic frequencies
- Secure boot
- TPM
- All security features
- Fast boot (MRC fast boot too)
- CRM 
- WI-FI
- Bluetooth
- AURA / any RGB
- Nativ ASPM
- MANY, MANY more settings so I'll just link guides intead of typing them all out...

These guides are only valid to be used in combination with GRUB or SCEWIN:

Intel:

https://docs.google.com/document/d/1ztCWHU2vCG9hnD_94VhlnsLJq1-0Mq7OwhjF79JsYgA/edit?tab=t.0
https://docs.google.com/document/d/1-7PxsfVJac_ooZEQe33eAE9oGo-32iXeDvVduCpJd-M/edit?tab=t.0
https://docs.google.com/document/d/1KIW7D9tCcv5sBBCh9qR6S-jZSsvTKQFwtOfBhkaBD4E/edit?tab=t.0
https://docs.google.com/document/d/1nDY2UcB7z2TewJKXJ2rK8Dl79PzbFaDefTHEtobhER4/edit?tab=t.0


AMD:

https://docs.google.com/document/d/1JhhSZqdbljHjNkLymoIRq67CiCLTISpZb2dm-gbpIs0/edit?tab=t.0
https://docs.google.com/spreadsheets/d/1Jw3lfH0uRFXMxnFGdpNfRpVvrQN-MVwaE0HSKoj-Xag/edit?gid=2060234474#gid=2060234474

SHOUTOUT TO ALL THESE AMAZING PEOPLE FOR MAKING GOOD LISTS <3



With that being said I'll finish off the BIOS section with saying that there's infinite things you can tweak and mess around with, don't get TOO carried away, if you have your main components dialed in and the power savings all off.
It'll be fine.
