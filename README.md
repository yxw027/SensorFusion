# SensorFusion
Using IMUs is one of the most struggling part of every Arduino lovers, here there is a simple solution.

![heading](https://image.ibb.co/cNL6n9/2.png)

This library will work with every IMU, it just need the raw data of gyroscope and accelerometer (the magnetometer isn't mandatory), it is based on these two libraries:
- https://github.com/PaulStoffregen/MahonyAHRS 
- https://github.com/PaulStoffregen/MadgwickAHRS 

I just made small modifications in the way the libraries handled the timing between two measurements and melted them together

## Installation
Use the arduino library manager or download directly from github

# About

Click on the video to see it on youtube

[![Alt text](https://img.youtube.com/vi/uhsOAhe9qgI/0.jpg)](https://www.youtube.com/watch?v=uhsOAhe9qgI)

please note that the Roll is inverted


I am using an STM32F103F103 known as blue pill but also any Arduino board will work

The IMU is a cheap mpu9250, you could find it everywhere for about 2€ (eBay, Aliexpress, ecc), to use it I strongly suggest you [this library](https://github.com/bolderflight/MPU9250)



If you wish use "IMU_tester" to see how well you IMU works (needs Processing)
Note: i am using also this very useful library: Streaming
