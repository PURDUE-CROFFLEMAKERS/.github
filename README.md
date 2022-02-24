# 2022 Purdue Project by Croffle

<hr>

## Project Title

    Drowsy Driving Prevention IoT System: Waking Up Driver Through Responsiveness Check

## Problem Statement

    Drowsy driving contributes a significant rate to car crashes and is a serious concern for drivers. According to the National Highway Traffic Safety Administration (NHTSA), 795 fatalities occurred due to drowsy driving.

    The detection and alert system of drowsy driving has developed since the automobile was invented. Previously developed systems were in-lab applicated systems, not ubiquitous. And the method to awake divers was non-interactive.


## Novelty

    1. Check the responsiveness
       => The IoT system gives tactile stimulus, which is vibration feedback when the driver feels drowsy. After the vibration is triggered, the application will check if the driver gives back the vocal sound feedback. By doing this, we can achieve an interactive system.
      
    2. Gamification of the awake process
       => Also, we will let the driver know how fast the driver reacts by giving voice feedback. This can make driver interested and encourage continuous interaction.

## System Overview

#### System Architecture

  <img src="./img/Architecture Diagram.jpeg"></img>
  
#### Flowchart

   **on-service**
  this is the diagram when system is on-service
  <img src="./img/Flowchart - Service.jpeg"></img>

  **personalize**
  process for collecting personalized data before system go on-service
  collecting personal data and calculate average of those data
  <img src="./img/Flowchart - Personalize1.jpeg"></img>
  <img src="./img/Flowchart - Personalize2.jpeg"></img>


## Environment Setting

#### ThingsBoard

    ✔️ HW: Raspberry Pi 4 with 1.5GHz quad-core CPU (2GB RAM)
    
    ✔️ OS: Ubuntu Desktop 21.10
    
    ✔️ ThingsBoard Version: thingsboard-3.3.3
    
    ✔️ Specific Settings:
       - ThingsBoard Queue Service: In memory (built in, default)
       - Dependency: openjdk-11-jdk, postgresql-12
  
#### React Native Application

    ✔️ React Native Verion: 0.67.2
    
    ✔️ Libraries:
       - Bluetooth: react-native-ble-plx (version 2.0.3)
       - HTTP: axios (version 0.25.0)
       - Sound Level: react-native-sound-level (version 1.1.5)

#### Arduino

    ✔️ Conponent:
       - Arduino Nano 33 IoT
       - MAX30102
       - Vibration Motor
       - Batery
    
    ✔️ Libraries:
       - Wire.h (Arduino AVR Boards 1.8.4)
       - MAX30105.h (SparkFun MAX3010x Pulse and Proximity Sensor Library 1.1.1)
       - arduinoBLE.h (ArduinoBLE 1.2.1)

## Team Members

    😎 Gyeyoung Jung
       - Chungnam National University
       - Major in Computer Science & Engineering
       
    😋 Sinyoung Bok
       - Chungnam National University
       - Major in Computer Science & Engineering
      
    🤓 Yesung Lee
       - Chungnam National University
       - Major in Computer Science & Engineering
       
    😳 Mirae Kwak
       - Chungnam National University
       - Major in Computer Science & Engineering
    
    😚 Heejung Kim
       - Chungnam National University
       - Major in Computer Science & Engineering
    
    🙂 William Park
       - Purdue University
       - Major in Cybersecurity & Network Engineering Technology
    
    😃 Alex Choi
       - Purdue University
       - Major in General CIT
