===
pyspace
===


IMU--True-Measurement-of-Roll-ptich-and-yaw
Filter comparisons, Angle estimations and recording of RAW outputs- using Kalman filters, python and Socket programming. 


Description
===========

Socket programming was used to eliminate the power and data cable harness, enabling more accuracy. The data from the MPU-9250 was trimmed to a lenght of 8. This 
could be adjusted for your application and could be implemented for various application including inverted pendulum projects, stabilty study and many more. Also 
fell free to play around with the delay values for adjusting the senstivity/sampling rate. 

Advantage: You can make your server completly standlone and wireless which means the cable harness willnot be causing any instablity to your system under study. 

All you need is a Wifi-router, IP address of the client, Raspberry Pi4, MPU9250 and a Python IDE (I used Pycharm).

Tip : Load the server code into Raspberry pi and make your PC as client. 

Watch this video below for more information. : https://youtu.be/WDkc80XHgts


