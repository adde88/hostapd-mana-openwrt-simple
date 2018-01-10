hostapd-mana-light 2.6 @ Pineapple NANO + TETRA / OpenWRT
===================================
hostapd-mana patches by Dominic White (singe) & Ian de Villiers @ sensepost (research@sensepost.com)  
ported to OpenWRT by: Andreas Nilsen @adde88  
This repo. is for building/installing ONLY the hostapd-mana binary  

Overview
--------
A access point (evilAP) first presented at Defcon 22.  

More specifically, it contains the improvements to the KARMA attacks we implemented into hostapd, as well as the ability to rogue EAP access points.  

Thanks to TarlogicSecurity who made the hostapd-wpe patches for OpenWRT, and inspired me to get the MANA patches running on OpenWRT.  

This will attempt to track the hostapd-mana releases from Sensepost.

Contents
--------
This repo. contains:
* hostapd-mana - modified hostapd that implements our new karma attacks

Dependencies
------------
Dependencies: libubus   
(You should run: "opkg update" before installing.)


Installation
------------
Install the IPK file located within the folder ./bin/ar71xx/packages/base/  
hostapd-mana-light_2.6-1_ar71xx.ipk  

Config-files will be installed to your usual folder:   
/etc/mana-toolkit/  

License
-------
The patches included in hostapd-mana by SensePost are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License (http://creativecommons.org/licenses/by-sa/4.0/) Permissions beyond the scope of this license may be available at http://sensepost.com/contact us/. hostapd's code retains it's original license available in COPYING.




