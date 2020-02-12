# controlthings-installer

Currently, the only official version of ControlThings Platform is the virtual image found at https://controlthings.io/platform.

# The following structions are incomplete...

With that said, for the adventurous, you are welcome to try to following steps to get a _mostly_ complete install of ControlThings Platform installed natively on your hardware.  This is an interim solution while I work on building a native installer for ControlThings Platform.

1) To start, you need to download and install Debian Testing on your machine.  The easiest way to do this is with the weekly network install (netinst.iso) from the Debian project.  Assuming you are running a 64bit Intel processor, here is the link:

>  https://cdimage.debian.org/cdimage/weekly-builds/amd64/iso-cd/debian-testing-amd64-netinst.iso

2) Install this ISO file to a USB drive.

3) Boot your machine  off the USB drive and install Debian with Gnome

4) Add ControlThings and Kali package repositories to your /etc/apt/sources file

5) Install the controlthings-full package.  This will take a while to download and install, especially if you have a slow Internet connection.
