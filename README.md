# Project Title
Virtual Reality Arm Gear

## Getting Started
* Clone the repo
* Install Contiki OS on SensorTAG
* Upload the files present in TI SensorTag on CC2650 sensortag
* Add the server file inside the RaspberryPi folder to RPI3
* Create a Unity Virtual Env using files present in Assests folder

## Prerequisites
* RPI3
* CC2650 Sensortag
* Contiki OS 2.2+

## Description
This project was made for the **Summer Internship, GAIP at National University of Singapore** under the supervision of Dr. Anand Bhojan, Dr. Chan Mun Chun and Dr. Tan Wee Kek. It provides an economical IOT solution created using CC2650, RPI3 and UNITY to mimic body motion which is projected on UNITY 3D model. 
Regular Physiotherapy Gamification for training paralyzed subject is the main target behind the project. It also aims on training muslces memory which can be beneficial for scenario such as safety drill and VR gaming. 

## Architecture
The architecture of the project is as follows:
* Two CC2650 tags are placed at the elbow and shoulder sending their Gyrosensor data to another SensorTag over Zigbee.
* A sensortag is attached to RPI using USB which acts as a Zigbee receiver dongle.
* The aggregated data is sent from Raspberry Pi to the server over UDP 
* This is forwarded to Unity which uses the GYRO reading to acutate the 3D model

<p align="center">
  <img src="https://github.com/RishabhSisodia/Virtual-Reality-Arm-Gear/blob/master/Layout.JPG" alt="Project Layout" width="600px" height="400px"/>
</p>


## Results
<p align="center">
  <img src="https://github.com/RishabhSisodia/Virtual-Reality-Arm-Gear/blob/master/demo_still.JPG" alt="Project Layout" width="400px" height="600px"/>
</p>

Click here to check the output video - [Link](https://github.com/RishabhSisodia/Virtual-Reality-Arm-Gear/blob/master/Live_Demo.mp4)


## Contributors

Created the project in a team with [Aayush Agarwal](https://github.com/aayush-ag21) at a month long internship at the National University of Singapore.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
