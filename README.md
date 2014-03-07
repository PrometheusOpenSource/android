Prometheus Open Source Project
=============================

Prometheus based on OmniROM


Getting Started
---------------

SETUP BUILD ENVIROMENT

Download Linux Distro

Prefer Linux Mint 64 Bits  [Download Link](http://mirror.umd.edu/linuxmint/images/stable/16/linuxmint-16-cinnamon-dvd-64bit.iso)

COMPLETE GUIDE FOR SETUP ALL ENVIROMENT  [XDA Guide](http://forum.xda-developers.com/showthread.php?t=2485160)


To get started with AnimeROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the Prometheus trees, use a command like this:

    repo init -u git://github.com/AnimeROM/android.git -b android-4.4

or use this:

    repo init -u https://github.com/PrometheusOpenSource/android -b android-4.4

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>
