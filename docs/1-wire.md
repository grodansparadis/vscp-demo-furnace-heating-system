# Setting up 1-wire

See [this page](https://pinout.xyz/pinout/1_wire#)

## Enable 1-wire support

You can do this with **sudo raspi-config** and enable under 1-wire support under **interface Options** and then restart.

In the graphical interface you can enable 1-wire support by going to **Menu > Preferences > Raspberry Pi Configuration**

Manually you can enable 1-wire support like this

```
sudo apt-get update
sudo apt-get upgrade

sudo nano /boot/config.txt
```

Add the line

> dtoverlay=w1-gpio

to and the 1-wire kernel driver. Then save and reboot.

```
sudo reboot
```

This [link](https://pinout.xyz/pinout/1_wire#) above list other options.

## List 1-wire devices

> ls ls /sys/bus/w1/devices/

generate something like

> 28-000003e71198  28-000003e75a74  w1_bus_master1

> cat /sys/bus/w1/devices/28-000003e71198/w1_slave

show something like

```
66 01 4b 46 7f ff 0a 10 2d : crc=2d YES
66 01 4b 46 7f ff 0a 10 2d t=22375
```

showing that the temperature is 22.375 degrees Celsius for this sensor and that the crc is good.

