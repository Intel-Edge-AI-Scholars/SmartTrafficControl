# Smart Traffic Control Intersection System

# Introduction
   In spite of successful development over the past decades, vehicle traffic control has been one of the most prominent global issues. While the traditional system has solved a lot of problems related to that, it still has some flaws.
	One of them is the fixed timer. Whether the road is clear or not, the signal will change its color after a number of seconds have passed. This unnecessary waiting not only causes inconvenience but also contributes to other problems like noise pollution, road congestion, etc. To solve this problem, the concept of smart traffic control system was introduced.
	Smart traffic control system , as the name suggests, is about applying artificial intelligence (Edge based, Cloud based or hybrid) and using sensors and camera to improve the efficiency of the traffic control with little human intervention required.
	Our project focuses on delivering such a system by enabling dynamic control of the traffic signal based on the number of cars moving. If the road is clear and safe for a defined period of time, the signal will change immediately.
![Image of Image-edgetotedge](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Flowimage.png)

# **FUNCTION**
   This project is built around the concept of background subtraction algorithm for vehicle counting along with object detection, object tracking, and event classification technique. 


### EDGE TO EDGE COMMUNICATION:
   Cameras mounted on the traffic signal will scan the area for car movements. Then it will relay the information to the other adjacent signals and help them make a decision based on the state of traffic on a road. If the path remains clear and safe for a defined period of time  then the signal will change immediately.  Diagram is given below:
![Image of Image-edgetotedge](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Image-edgetoedge.jpeg)

### Cloud Integration
   We also plan to use popular cloud-based services like Google maps to give the travellers information regarding the state of a traffic route using the data taken from the traffic signals in order to maximize the efficiency of our system. 

### SIGNAL CONTROL RULES

	
### Emergency vehicle detection
   A separate sensor that will transmit the override command for ambulances, police vehicles and other emergency-related situations.

### Prerequisites

 - Software:
   - Windows or Linux operating system
- Hardware:
   - Intel 6th Generation based processors
   - Minimum 8 GB RAM
- TOOLS
   - Dockers
   - Google Map service
   - Intel OpenVINO


### Results
   The following screenshots is the result of our project after using different videos, captured with different cameras with different angles:

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data1.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data2.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data3.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data4.jpeg)
