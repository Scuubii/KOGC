# BIOS / INTER-SETUP

Welcome to the next step—congrats on surviving the hardware rant! More of that to come...
Why call this INTER-SETUP? Simple: it’s the stage between the PRE-SETUP and POST-SETUP. Deal with it.

# BIOS Configuration Overview

The BIOS (Basic Input/Output System) is a powerful and complex part of your system, and there's a lot you can tweak here. Rather than reinventing the wheel, I’ll link some excellent guides and provide a roadmap on how to follow them.

## Before You Begin

Before you dive into the BIOS, familiarize yourself with the CMOS battery and how to reset it. If your BIOS settings ever mess things up, resetting the CMOS will bring everything back to factory defaults. Many high-quality motherboards have a dedicated button for this, saving you from disassembling your computer.


## Unhiding Advanced BIOS Settings

Some BIOS options are hidden by default. To unlock them, you’ll need tools like GRUB and SCEWIN. Most of the guides I’ll link use SCEWIN, which I highly recommend.


## Manual BIOS Tweaks

When manually configuring your BIOS, a general rule is to turn off anything unnecessary. Here's a checklist of features you should disable for a performance-focused setup:

- Power Saving Features: Anything labeled as power-saving or efficiency-focused.
- Spread Spectrum: Turn off "spread spectrum" and anything related to it.
- Dynamic Adjustments: Disable features like dynamic cores, dynamic voltage adjustments, Speedstep, and Speedshift.
- Secondary Processing Units:
- On Intel: Disable E-cores.
- On AMD: Disable the second CCD for multi-CCD processors.
- Hyperthreading (Intel) / SMT (AMD): Disable these unless specifically needed.
- Virtualization Features: Turn off VT-D, IOMMU (AMD), and any virtualization technologies unless you explicitly need them.
- C-states: Disable all power-saving states.
- Frequency Scaling: Turn off Speedstep, Speedshift, and anything similar.
- Security Features:
- Secure Boot
- TPM
- All other security-related settings.
- Fast Boot: This includes both standard and MRC Fast Boot.
- Miscellaneous: Disable CRM, native ASPM, Wi-Fi, Bluetooth, RGB (e.g., AURA Sync), and anything else not essential for  performance.
- There are many other minor settings to tweak, but listing them all here would take forever. Instead, I’ll link some detailed guides below.

## Guides for GRUB and SCEWIN Tweaks

For advanced BIOS adjustments, these guides are indispensable:

## Intel:

[Ancel's guide](https://docs.google.com/document/d/1ztCWHU2vCG9hnD_94VhlnsLJq1-0Mq7OwhjF79JsYgA/edit?tab=t.0)

[Intel Grub List by @kapselegg](https://docs.google.com/document/d/1-7PxsfVJac_ooZEQe33eAE9oGo-32iXeDvVduCpJd-M/edit?tab=t.0)

[Hidden Intel BIOS settings list](https://docs.google.com/document/d/1KIW7D9tCcv5sBBCh9qR6S-jZSsvTKQFwtOfBhkaBD4E/edit?tab=t.0)

[Grub list by Vost](https://docs.google.com/document/d/1nDY2UcB7z2TewJKXJ2rK8Dl79PzbFaDefTHEtobhER4/edit?tab=t.0)


## AMD:

[Ryzen SCEWIN / Grub](https://docs.google.com/document/d/1JhhSZqdbljHjNkLymoIRq67CiCLTISpZb2dm-gbpIs0/edit?tab=t.0)

[AMD BIOS Optimization Spreadsheet](https://docs.google.com/spreadsheets/d/1Jw3lfH0uRFXMxnFGdpNfRpVvrQN-MVwaE0HSKoj-Xag/edit?gid=2060234474#gid=2060234474)

Shoutout to these amazing creators for their contributions! <3


## Final Thoughts on BIOS Tuning

The BIOS is a treasure trove of tweaks and customizations, but don’t let it overwhelm you. Stick to dialing in your main components and disabling unnecessary power-saving features. Once you’ve handled the essentials, your system will be in great shape.


[SOFTWARE](https://github.com/Scuubii/KOGC/blob/main/software.md)

