[![ MMA7660FC](MMA7660FC_I2C.png)](https://store.ncd.io/product/mma7660fc-3-axis-orientationmotion-detection-sensor-%C2%B11-5-g-accelerometer-i2c-mini-module/).

#  MMA7660FC

Manufactured by Freescale Semiconductor, Inc., the MMA7660FC 3-Axis Digital Accelerometer is a low power, micro-machined sensor capable of measuring acceleration along its X, Y, and Z axis.
This Device is available from www.ncd.io 

[SKU: MMA7660FC]

(https://store.ncd.io/product/mma7660fc-3-axis-orientationmotion-detection-sensor-%C2%B11-5-g-accelerometer-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MMA7660FC motion detector and 3axis accelometer sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mma7660fc-3-axis-orientationmotion-detection-sensor-%C2%B11-5-g-accelerometer-i2c-mini-module/">MMA7660FC motion detector and 3axis accelometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MMA7660FC.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
