# Bypass_charging settings using Terminal

For On --> 
echo 0 > /sys/class/power_supply/battery/charging_enabled

For Off --> 
echo 1 > /sys/class/power_supply/battery/charging_enabled
