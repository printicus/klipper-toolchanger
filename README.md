# klipper-toolchanger

This is a fork from viesturz of his Klipper-Toolchanger plugin.

https://github.com/viesturz/klipper-toolchanger

For now it is what I use in my setup. Text that comes next is what viesturz wrote(with some of my modification):


An assortment of Klipper extensions that I have made while working on [Tapchanger](https://github.com/viesturz/tapchanger)

# Installation

To install this plugin, run the installation script using the following command over SSH. This script will download this GitHub repository to your RaspberryPi home directory, and symlink the files in the Klipper extra folder.

```
wget -O - https://raw.githubusercontent.com/printicus/klipper-toolchanger/main/install.sh | bash
```
Add the [macros.cfg](/macros.cfg) to your printer config.

## Updates that add new files

Note that if an update has new klipper files, they **will not** be automatically installed into Klipper.
You will need to run the intall script manualy to add them:
```commandline
bash ~/klipper-toolchanger/install.sh
```

# Components

* [Toolchanger](/toolchanger.md) - tool management support.
* [Tool probe](/tool_probe.md) - per tool Z probe.
* [Rounded path](/rounded_path.md) - rounds the travel path corners for fast non-print moves.
* [Tools calibrate](/tools_calibrate.md) - support for contact based XYZ offset calibration probes.
