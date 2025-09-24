# home_monitoring_robot
This IOT based "HOME MONITORING" is  used to monitor the home using different types of sensor. The goal of this project is to build a home security monitoring system with Raspberry Pi based on telegram messenger bot.

ABSTRACT:

This system is able to monitor the security of the house from burglars or intruders, notify the temperature of the house and detect smoke or gas. All the sensor value recieved is sent to IoT cloud Thingspeak. We are using Raspberry Pi as the control center of the system and esp8266 wifi to upload the value in a cloud of Thingspeak. Gas sensor, LDR sensor, ultrasonic sensor, metal sensor, fire sensor, DHT 11 sensor, and robot setup all are done in this project. If any environmental problem occurs in the home means, then sensor senses the value and it will upload the changes in cloud.  Gas sensor finds any leakage of LPG and LDR is used to measure the light intensity. The ultrasonic sensor is used to find the distance of  robot and any sudden movements in environment. The metal sensor finds small sized pieces of metal in home and if any fire disaster occurs means the fire sensor sense's it and pump motor  pumps  the water at the same value sent to IoT cloud. DTH 11 sensor senses the humidity level and temperature level inside home. Telegram is used as a liaison application to send notifications from Raspberry Pi to tool users. Notifications sent in the form of pictures of the state of the room in the house, temperature conditions and gas density conditions and all other updates are sent.


INTRODUCTION:

 • The Internet of Things is a concept to make every device/system such as Internet TV’s, smart phones and sensors connected with the Internet can be controlled and monitored from anywhere and anytime. 
 • There are various existing systems that are used for home security purposes such as Microcontrollers - based wired and wireless security systems, CCTV system etc, but they are much expensive and having limitation in range and accessibility to the user.
• In this project work, cost effective Raspberry Pi based home monitoring system is designed. 
According to the national statistics agency level of crimes especially those affecting households such as theft and robbery still often occur despite fluctuations. 
Recently the number of theft and robbery with violence against households was at 1,628,634. Out of 100,000 people, 14,000 of them are at risk of crime. 
Many thefts occur when homeowners are traveling and the house is left for a long time. 
In addition to the risk of theft, the house whose owner is traveling also risks fire due to various factors. Such as electrical zippers, and gas leaks.
In some housing environments, security are already available, but they are less efficient when there are security or fire disturbances.
This is because the information received is not real-time. Information that is not real-time results in slow handling in case of monitoring.
However, CCTV does not give notice in real-time when recording interference.
If the owner does not see the installed CCTV display, then the homeowner will not know the condition of the house.
For that, we need a tool that can monitor the state of the house and notify you directly when someone has been unnoticed or there are other unexpected events. 
Here,  monitoring robot which is self automated, connected to the Raspberry Pi and tool can be accessed using Telegram messenger bot to give instructions and get updates. 
Use of Raspberry Pi which is an inexpensive, small and portable computer board. 
Raspberry Pi is easy to use but powerful, affordable and apart from being hard to break.

Sending information in real-time using to the user and Telegrams can respond to certain texts according to the commands we give.
The camera used for monitoring is a Raspicam camera. If one of the sensors is active, it will trigger the camera connected to the Raspberry Pi to take photos and send notifications via the Telegram messenger application. 
After that, the bot on Telegram Messenger offers what we want to do next, there two possibilities can be done by this bot, which is to take a photo or video of the situation at home at that time and send it back to the user. 
This tool is expected to be able to monitor the state of the house and send notifications to the homeowner if there is interference with the house.


PROBLEMSTATEMENT: 

• In view of the present family security coefficient and poor family environment information controls were complicated, family members can’t access to environmental information. 
This project can be used for security purposes where we need to get information about some suspicious area/people. 
Earlier the robots were controlled through wired networks but now to make robot more user friendly, they are framed to make user commanded work. 
In the market there are several types of home security systems, but some examples of products offered are less than provide more flexibility in their use. 
Provision of type and number of devices in the form of limited sensors and prices offered are relatively expensive.  


OBJECTIVES:

• To develop an IOT technology based robot, which can be controlled by a mobile devices/ computer over the Internet/Wi-Fi from anywhere at anytime. Evaluate and study the platform required for the system. 
• To store and retrieve the necessary data on the families mobile phone using realtime sensor facilitating real-time monitoring and doing day-to-day activities autonomously using smart sensors and even integrating the concept of  “CloudComputing”  in their overall data management.      


PROPOSEDMETHODOLOGY:

• The ultimate goal of this project is to design and construct a robot to move into different locations and receive the details of that area with the helpof inbuilt sensors on it. 
• We are well aware that every hardware system has a main component (also called as brain of the system) which is used to control the system by giving a set of instructions. 
• Here, the Camera is used for surveillance purpose as well as for controlling the L298N Motor Driver module. 
• The L298N Motor driver is used to control DC motor for both speed and rotating directions. 
• The PWM technique is used to vary input voltage in order to control the speed of the motor while the H-Bridge circuit is used for controlling the rotation direction of the motor. 
• Raspberry Pi is used to control the sensors like MQ2 Gas Sensor and FlameSensor mounted on the robot.
 • MQ2 Gas Sensor is used to detect the presence of gases like LPG, CO and Smoke. Internet of things of the family embedded robotic system we used to monitor family in through video streaming. 
• SSH protocol to ensure that the remote control and the safety reliability of the robot.
This system consists of measuring the home environment using sensors and robots.
The sensor value is stored as an IOT cloud.
If any obstacle detected means the robot automatically turns right and moves forward.
In this project, we have used six types of sensors to measure environmental conditions in the home.
The sensor is input for Raspberry Pi and buzzer, relay board, and robot setup.
The Wi-Fi is using to upload the sensor measured value in the IoT cloud.
The relay board is operated the pump motor. 

Hardware Requirements:

Raspberry Pi
NodeMcu esp8266
DHT 11 sensor
L298N Motor Driver
Ultrasonic sensor
Metal sensor
LDR sensor
H-Bridge circuit
MQ2 Gas sensor
Fire sensor
Relay board
Pump motor
Robot setup

Software Requirements:

Raspberry Pi OS
OrCAD Design
Thingspeak  application
Telegram Chat Bot

Applications:

Multitasking robot :
With different types of sensors environment around the user can be easily kept under control and safe.

Self automated :
Independent and does work when instructions are given.

Gaurds designated area :
To stay within an area, security personnel use mapping software to create a geo-fenced perimeter. There’s also an ultrasonic sensor for detecting objects close to the robot. 

Used in various fields:
In further applications, for military purposes, hospitals and other places.

ADVANTAGES: 

Monitoring purpose:
 The bot can be used to inspect areas which are difficult/risky for humans. This avoids costly precautions which are used to safeguard humans. 
Easily accessable:
Bot is portable hence it has advantage over cctv or any other static surveillance system.
Low Cost:
When compared to aurdino based it is cheaper and more powerful. A bot with cheap price can be designed where discontinued surveillance is required. 

DISADVANTAGES: 

Network problem:
The entire system depends on Internet access. So, if the network goes down,the system becomes inactive. 
Easily hackable:
The system is vulnerable to hackers who can penetrate the system and control it without the knowledge of the owner. 


CONCLUSION:

Based on the results of research that has been done on home security monitoring system tools with Raspberry Pi-based telegraph messenger, it can be concluded that, in designing and building a home security monitoring system tool with Raspberry Pi based on a telegram messenger, there are several stages, namely the design of the tool design, the assembly of the device on the casing, the making of the program code to the testing of the tool. In testing the home security monitoring system tool that has been made with several sensor components mounted on a casing box is running well, both the DHT22 sensor installation with Raspberry Pi, MQ2 sensor with Raspberry Pi and Raspicam sensors. After testing this home security monitoring tool can be an early warning if there is theft, gas leak, and fire. This tool connected with a telegram messenger with the help of a wifi connection and were able to send a messages in real-time to house owner.
