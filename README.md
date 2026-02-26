# Bypass_charging settings using Terminal
------------
Terminal with Root Access 
su 
--
For Turn On Bypass Battery Charging 
```
echo 0 > /sys/class/power_supply/battery/charging_enabled
```
For Turn Off Bypass Battery Charging
```
echo 1 > /sys/class/power_supply/battery/charging_enabled
```
