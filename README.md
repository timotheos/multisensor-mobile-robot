# Multisensor Mobile Robot

This will be the start of me trying to be a robotics developer.  

I am still in the process of learning many things, but it will all start here.  

This repository comprises of ROS packages needed to run the Pioneer3 AT robot with multiple sensors mounted on top it, namely the SICK LMS200, the Hokuyo YVT-35LX, and the Hokuyo UTM-30LX.

### Things to note
- SICK LMS200 needs to be set to a higher baud rate (38400bps) when it has been reset to factory settings. This baud rate can only be obtained when using a RS422  

   References:
   - [sicklms failed to initialized:failed to detect baud rate!](https://answers.ros.org/question/12018/sicklms-failed-to-initializedfailed-to-detect-baud-rate/)  
   - [SICK LMS-200 / LMS-291 LIDAR LASER SCANNER RS-232 INTERFACING WITH UBUNTU & R.O.S.](http://www.digital-circuitry.com/Wordpress/sick-lms-200-lidar-laser-scanner-interfacing-with-ubuntu/)
