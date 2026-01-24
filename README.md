# Bypass_charging settings using Terminal
For Turn On Bypass Charging 
```
echo 0 > /sys/class/power_supply/battery/charging_enabled
```
For turn Off Bypass Charging
```
echo 1 > /sys/class/power_supply/battery/charging_enabled
```

N.B - Use Terminal With Root Access
