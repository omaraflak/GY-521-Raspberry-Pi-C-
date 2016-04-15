# GY-521 Raspberry Pi C++
This class allows you to get datas from the GY-521 sensor on Raspberry Pi AND in C++ !

1) Download WiringPi library

    git clone git://git.drogon.net/wiringPi
    cd wiringPi
    git pull origin
    cd wiringPi
    ./build

2) Use my class like this:

    Sensor sensor;
    int x = sensor.getGyroX();
    int y = sensor.getAccelY();
    int z = sensor.getAngleZ();
    
Sample: https://github.com/omaflak/GY-521-Raspberry-Pi-C-/blob/master/libSensorSample.cpp
