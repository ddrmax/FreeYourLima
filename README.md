# FreeYourLima
A github repository to help you regain the control of your Lima Ultra device

## Disclaimer
I'm not responsible in any cases if you brick your device by using any of the tutorials I or the community will be posting

## What to do first?
Please go Check out how to root your Lima [here](https://github.com/catwell/postlima)

## State of the Work.
The  work is still in it's initial state but I broke down the majority of how the hardware and software is and I'm currently playing with the device to disable most of the Lima and services related with actualy near no success (the device reboots itself after a while when disabling some services)

## Is it sure that it will work with my Lima?
Actually Yes, We have laying arround two of revisions of the board (The First board had a usb power problem, thanks to [@catwell](https://twitter.com/pchapuis/status/1127898174289584128).


## What is actually planned?
- Completting the Wiki with all the information that I have already extracted from the device.
- A video or Wiki with some photos on how to open your device in a non destructive manner
- Making the device clean enougth for another uses (disabling all non lima related services) to get more Ram to work with
- Making it a simple Nas with a Samba Share (no downloads nedeed, only backing up some files via WinSCP and replacing them with the ones from the repository and rebooting the device)
- Making it a nextcloud instance (maybe based on sqlite)
- Adding an auto update and a automated package installer like apt or Yum dowloading apps from Gumstick or a self made server
- Cooking updated apps (The gumstick server have packages with the same version as the lima or maybe a little newer but outdated)
- Cooking a new distro ?
- Making a web interface to configure the device (Router like or NAS like interface)

## What do you say from "Cooking a new distro"
If we have a simple way (for example putting an img file into a flash drive and running it and flashing it to the eMMC i will try to make one that can replace the actual distro.
possible distros are these:
- an headless debian
- an newer pocky distro (upgrade the 2.1.1 from the lima one to the 2.4 one) why not the 2.6 or 2.7? No support for armv7hf in it.
- an headless arch Linux
- all of the others but with pre installed packages for specific usages (NAS / Cloud / NVR / Plex server / etc..)
