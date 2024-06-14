# Smart buoy

Smart Buoy is an IoT system to monitor waves recordered with an IMU sensor positioned on a buoy and to compare the acceleration with the weather forecast.
If a data analysis is performed, a relationship can be established between waves monitored by the IMU and wave height provided by the forecast.
If the measured data provide values inconsistent with the established relationship, it means that the natural waves have been altered (e.g. due to powerboat passage effects) or that the forecast is not correct.

## Hardware required:
- an phone with IMU and GPS, that acts as signal recording and transmission system
- a PC

## Software required
- [node-red](https://nodered.org/) (on the PC) with the following:
  - node-red-dashboard
  - -node-red-contrib-web-worldmap
- [Sensor Logger](https://www.tszheichoi.com/sensorlogger) (on the phone)

## Free online accounts required
- [HiveMQ](https://www.hivemq.com/)
- [OpenWeatherMap](https://openweathermap.org/)

## HiveMQ setup
Create an account and obtain a cluster serverless URL [see image](account.huvemq.png)
