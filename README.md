# Motorcycle TPMS
Motorcycle iTPMSystem Client Software  
Author: Keith Conger <keith.conger@gmail.com>  
http://development.thecongers.org/home/mtpms  
License: GPLv2


## Download app
[F-Droid](https://f-droid.org/packages/org.thecongers.mtpms/)  
[Play store](https://play.google.com/store/apps/details?id=org.thecongers.mtpms)    

## Requires
* An iTPMSystem (http://www.atbs.com.tw/product_TPMS_Module_E.htm)

## Current features
* Displays tire pressure, temperature and voltage
* User configurable units for pressure and temperature
* User configurable notifications for low/high tire pressure (Sound, vibrate and LED)
* Auto night mode(dark color scheme) using the light sensor
* Sensor discovery
* Screen rotation
* Runs in the background
* Optional data logging in csv format to /sdcard/mTPMS
* English language, please contact me if you would like to help with a translation

## How to use
1) Power on the iTPMSystem
2) Pair your device to the iTPMSystem unit, test with the Vendor supplied app and close it.  If it doesn't work then this app probably won't either.
3) Launch iTPMSystem, you should see message that you are connected.  You now need to wait for the sensors to start sending data through the iTPMSystem.
4) Once discovered map them to their wheel locations in the preferences.
5) Enjoy

## Software Used  
Android SQLiteAssetHelper  
https://github.com/jgilfelt/android-sqlite-asset-helper

SVG TPMS Icon sourced from:  
http://commons.m.wikimedia.org/wiki/File:TPMS_warning_icon.svg

## Donate  
If you find any of this useful and want to show appreciation see below:

Play Store: https://play.google.com/store/apps/details?id=org.thecongers.mtpms  
PayPal: keith.conger@gmail.com  
Bitcoin: 1Pg54vVnaLxNsziA6cy9CTefoEG5iAm9Uh
