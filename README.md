# Bypass_charging settings using Terminal
------------
Terminal with Root Access
--
For Turn On Bypass Charging 
```
su
echo 0 > /sys/class/power_supply/battery/charging_enabled
```
For Turn Off Bypass Charging
```
su
echo 1 > /sys/class/power_supply/battery/charging_enabled
```
