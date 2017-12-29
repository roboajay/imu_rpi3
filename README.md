# imu_rpi3

The steps are well documented here at: http://kingtidesailing.blogspot.in/2016/02/how-to-setup-mpu-9250-on-raspberry-pi_25.html

the error i faced here:

I was unable to calibrate imu and today i did (reason was missing of certain java packages)
after that i proceed according to 
1. http://kingtidesailing.blogspot.in/2016/02/how-to-setup-mpu-9250-on-raspberry-pi_25.html
the final step is to run a python script but i got error, when googles it nothing came(literally juts the github came again)

other people also face this error and it not yet solved in official rpi3 fprum:
https://www.raspberrypi.org/forums/viewtopic.php?t=174526

Now i moved on to various other website:

  2. https://github.com/AndFroSwe/MPU9250-RPi
works well but no values came seems like skeleton code and we have to develop further

  3. https://github.com/rpicopter/MotionSensorExample
Full developed code, i just did all the things in readme.md but didn't work (i can search this error tomorrow , have intuition that it will work, if digged little deeper)

  4. https://github.com/MomsFriendlyRobotCompany/mpu9250
package has issues for sure...

 5.https://github.com/ControlEverythingCommunity/MPU-6000
works and sends some value but the question is what value is it sending and is it correct?

6.https://github.com/mpolaczyk/Gyro-L3GD20-Python/blob/master/Example_ReadRawData.py
	IO error

7. http://ozzmaker.com/guide-to-interfacing-a-gyro-and-accelerometer-with-a-raspberry-pi/
8. http://www.telesens.co/2017/03/11/imu-sampling-using-the-raspberry-pi/
	Sample code but with detail, will try later if nothing else works

