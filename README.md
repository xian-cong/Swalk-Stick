# Swalk Stick
### Introduction
**Swalk Stick** (Smart Walking Stick) idea was originally designed and prototyped by **The Innovative 3**, consist of Koay Xian Cong, Lim Wei Chung and Crement Ong in December 2016. The first design was originally prototyped using PVC pipes as a **proof of concept (POC)**. The prototype was being used to compete in Young Innovative Challenge State Level and we won the first prize. Since then, our team got bigger after Owen Loh and Lee Zong Junn joined and changed to **Team Voltage**. My team and I represented our school in various competitions and exhibitions with the Swalk Stick including: 
  1. Chung Ling High School Centenary
  2. Turning Research into Ideas Workshop
  3. International Technology & Science Symposium at Penang, Malaysia
  4. SIRIM Technology Expo
  5. Penang International Science Fair
  6. STEM Carnival Invention Competition
  7. Presented to Royal Princess from Thailand, Maha Chakri Sirindhorn
  8. Presented to the ambassador of Hungary to Malaysia, Petra Ponevacs-Pana

### Contents
  1. [Introduction](https://github.com/xian-cong/Swalk-Stick#introduction)
  2. [Contents](https://github.com/xian-cong/Swalk-Stick#contents)
  3. [Objectives](https://github.com/xian-cong/Swalk-Stick#objectives)
  4. [Functions](https://github.com/xian-cong/Swalk-Stick#functions)
  5. [Hardware Connection](https://github.com/xian-cong/Swalk-Stick#hardware-connection)
  6. [Software]
  7. [Design](https://github.com/xian-cong/Swalk-Stick#design)
  8. [Prototype Generations](https://github.com/xian-cong/Swalk-Stick#prototype-generations)
  9. [Future Improvements]

### Objectives
  1. Personal Emergency Assistant
  2. 24 hours Safety Monitor
  3. Risk Avoidance

### Functions
The Swalk Stick has 3 main functions: 
  1. Fall Detection System
  2. 24/7 Monitoring of User's position for Rapid Medical Assistance
  3. Automaed Lights at Night
  4. Obstacle Detection

### Hardware Connection
- Gyroscope sensor to detect the fall of the user.
- Temperature sensor to detect the surrounding temperature and humidity.
- GPS sensor to locate the exact position the user is.
- SMS Module sensor to send messages to the user’s family members in the case of an accident.
- Vibration motor to vibrate the walking stick if obstacles in close proximity are detected.
- Bluetooth module to send data to close range devices.
- RTC module to log down time.
- SD Card module to log down data.
- Buzzer to notify surrounding people for 10secs when user falls.
- LED strip to be switched on automatically in the dark.
- LDR to be detect light intensity to control LED strip.

<h4 align="center"> <img src="https://github.com/xian-cong/Swalk-Stick/blob/main/Photos/image.MJVEG1.png" width="500"> </br>

### Software
Arduino code of the following project can be found [here](https://github.com/xian-cong/Swalk-Stick/blob/main/Programming_Code_Final/Programming_Code_Final.ino).

### Design
The first generation Swalk Stick was mainly used as a POC rather than making it looked like a real product. During second generation, the Swalk Stick was designed using AutoCAD which can be found [here](https://github.com/xian-cong/Swalk-Stick/blob/main/Walking-Stick-full-3D.dwg) and printed out. The 3D design is shown below.
    <h4 align="center"> 
  </br><img src="https://github.com/xian-cong/Swalk-Stick/blob/main/Photos/Walking%20Stick.png" width="100">
  <img src="https://github.com/xian-cong/Swalk-Stick/blob/main/Photos/DSC05832.JPG" width="250">  


### Prototype Generations
**First Prototype** </br>
<h4 align="center"> 
  <img src="https://github.com/xian-cong/Swalk-Stick/blob/main/Photos/1498356792250.png" width="100">

  </br> <h4 align="left">Second Prototype </br>
<h4 align="center"> 
  <img src="https://github.com/xian-cong/Swalk-Stick/blob/main/Photos/DSC05844.JPG" width="150">
</br>
  
### Future Improvements
- Implement Computer Vision to for object detection rather than using ultrasonic sensor.
- Modifying code by implementing sleep mode on microcontroller to save battery when not being used.
- Using other communication technologies rather than SMS.

### Additional Information
Additional Information/Portfolio of projects can be found [here](https://github.com/xian-cong/Swalk-Stick/tree/main/JPEG).
