A collection of programs and modules for use on the esp8266 with lua firmware
======

bin/
----

Some firmwares that were built locally while waiting for the official ones.

mqtt/
--------

Examples of programs that read the temperature and publish the reading to MQTT.

ds3231/, ds1307/, lm75/, pca9555/, at24c32/
-------

Basic manupulation of some i2c modules.

reBoot.lua
----------

A test program that repeatedly reboots (3 seconds dsleep). Used to test the wakeup problem.

reCount.lua
-----------

A test program that repeatedly increments a counter in a file, then reboots (3 seconds dsleep). Used to test the wakeup problem.

reRead.lua
----------

A test program that repeatedly reads the ds18b20, then reboots (3 seconds dsleep). Used to test the wakeup problem.

reWiFi.lua
----------

A test program that waits for WiFi to acquire an IP, then reboots (3 seconds dsleep). Used to test the wakeup problem.
