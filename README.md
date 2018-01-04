<img src="https://raw.githubusercontent.com/grm34/archboot/master/img/archboot.png" width="640">

[![version](https://img.shields.io/badge/archboot-v2.7.3-blue.svg)](https://github.com/grm34/archboot/releases) [![Build Status](https://travis-ci.org/grm34/archboot.svg?branch=master)](https://travis-ci.org/grm34/archboot) [![Gitter](https://badges.gitter.im/grm34/archboot.svg)](https://gitter.im/grm34/archboot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![author](https://img.shields.io/badge/author-grm34-red.svg)](https://github.com/grm34) [![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/grm34/archboot/blob/master/LICENSE)

This script perform an automatic install of ArchLinux. Pretty simple, it only ask you for hostname, username, password, which disk to use, required partitions sizes and if you wish or not to install a desktop environment.

## Requirements

The only thing you need is one **USB bootable device** of [ArchLinux](http://mir.archlinux.fr/iso/latest) and one **HDD dedicated** for the installation (see USB Boot instructions for [Windows](https://rufus.akeo.ie/?locale=fr_FR) or for [Linux](https://debian-facile.org/doc:install:usb-boot)).

## Usage

**1.** Reboot your computer, open Boot Selection Menu and boot on the USB bootable device.

**2.** On the install menu of ArchLinux, select [Boot Arch Linux (x86_64)](https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png).

**3.** For AZERTY keyboard run: `loqdkeys fr`

**4.** Download archboot and follow the instructions:

`wget tiny.cc/archboot; sh archboot`

## Notes

For list of all available languages and regions codes, please see [languages](https://github.com/grm34/archboot/blob/master/conf/languages) and [regions](https://github.com/grm34/archboot/blob/master/conf/region_city).

If you want to see whose packages are installed by this script, please see [Applications Folder](https://github.com/grm34/archboot/tree/master/src/apps).

And for GPU Drivers and support, please see [GPU Drivers](https://github.com/grm34/archboot/blob/master/src/desktop/gpu).

## Logs

For full installation logs, take a look in **/var/log/archboot**

`cat /var/log/archboot/archboot_*.log`

## Screenshot

[![OS](https://img.shields.io/badge/Archlinux-xfce4-blue.svg)](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)
![](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)

## Official Documentation

Take a look at [ArchLinux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide) to view the official documentation.
