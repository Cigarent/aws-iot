Setup Temperature and Humidity Sensor for Raspberry Pi
=========================================================

First Install I2C on Raspi
--------------------------
Reference[https://learn.adafruit.com/adafruits-raspberry-pi-lesson-4-gpio-setup/configuring-i2c]
```
sudo apt-get install python-smbus
sudo apt-get install i2c-tools
```
*Installing Kernel Support (Manually)

### testing I2C
```sudo i2cdetect -y 1```

Install NodeJS module
---------------------
