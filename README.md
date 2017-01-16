# BthSwitch.kext
Enable AR5B195 Bluetooth switch on macOS

Description
----

Normally the Atheros Bluetooth module can not be turned off on macOS. This driver can inject the Product ID (pid) of Atheros Bluetooth to enable the bluetooth switch.

This driver is suitable for the bluetooth module with the following pids:
* 0cf3:3000
* 0cf3:3001
* 0cf3:3002
* 0cf3:3003
* 0cf3:3004
* 0cf3:3005

You can install it using your favorite kext installer, such as Kext Utility.

Download
----
[Click here](https://github.com/coslyk/BthSwitch.kext/archive/master.zip "Download")
