# BthSwitch.kext
Enable AR5B195 Bluetooth switch on macOS

Description
----

The Atheros Bluetooth module can not be turned off on macOS. This driver can inject the Product ID (pid) of Atheros Bluetooth to enable the bluetooth switch.

This driver is suitable for the bluetooth module with the following pids:
 * 0cf3:3000
 * 0cf3:3001
 * 0cf3:3002
 * 0cf3:3003
 * 0cf3:3004
 * 0cf3:3005

