![image](https://github.com/wytalfred/Beaglebone-magnetometer-Qt-display/raw/master/mag01.jpg)

I'm using a LCD4 cape to display a triangle which will keeping pointing to north.

The magnetometer I'm using is HMC5843. It's an I2C device. It's part of the GY-80 module. You can easily get access to documents about GY-80 on the Internet.

Fortunately, Beaglebone Black already has its driver pre-built. So all I have to do is use it, which is not very difficult.

I'm using Qt4 for graphic programming. I'm new to Qt.


USAGE


./imu-setup

./newtest -qws
