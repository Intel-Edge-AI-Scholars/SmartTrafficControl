# *Smart Traffic Control Intersection System*

### Introduction
   In spite of successful development over the past decades, vehicle traffic control has been one of the most prominent global issues. While the traditional system has solved a lot of problems related to that, it still has some flaws.
	One of them is the fixed timer. Whether the road is clear or not, the signal will change its color after a number of seconds have passed. This unnecessary waiting not only causes inconvenience but also contributes to other problems like noise pollution, road congestion, etc. To solve this problem, the concept of smart traffic control system was introduced.
	Smart traffic control system , as the name suggests, is about applying artificial intelligence (Edge based, Cloud based or hybrid) and using sensors and camera to improve the efficiency of the traffic control with little human intervention required.
	Our project focuses on delivering such a system by enabling dynamic control of the traffic signal based on the number of cars moving. If the road is clear and safe for a defined period of time, the signal will change immediately.
	
![Image of Image-edgetotedge](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Flowimage.png)

# **CORE CONCEPTS OF OUR DESIGN**
   This project is built around edge A.I, background subtraction algorithm for vehicle detection along with object detection, object tracking, and event classification technique. This system is also augmented with machine learning algorithms for decision making.
   
# **FUNCTION**
   This project is built around the concept of background subtraction algorithm for vehicle counting along with object detection, object tracking, and event classification technique. 


### EDGE TO EDGE COMMUNICATION:
   Cameras mounted on the traffic signal will scan the area for car movements. Then it will relay the information to the other adjacent signals and help them make a decision based on the state of traffic on a road. If the path remains clear and safe for a defined period of time  then the signal will change immediately.  Diagram is given below:
![Image of Image-edgetotedge](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Image-edgetoedge.jpeg)

### Cloud Integration
   We also plan to use popular cloud-based services like Google maps to give the travellers information regarding the state of a traffic route using the data taken from the traffic signals in order to maximize the efficiency of our system. 

### Data Transmission:
  The data is then transmitted to popular cloud-based services like Google maps to give the travellers information regarding the state of a traffic route using the data taken from the traffic signals in order to maximize the efficiency of our system. 

### SIGNAL CONTROL RULES
   In order to make our project understand traffic signal rules, we have used the following mathematical formula:
   	``` T.C = (Pd, Sd) ```
 The traffic control rules T.C can be assumed as a pair of boolean vectors. In the above-mentioned formula, Pd is the first set of direction vectors that allows primary traffic to flow. Sd is the second set of direction vectors which allows the model to let a lane flow if the primary lane has yielded.
  Another thing to note is that this project is considering a simple binary traffic light only, with two states; true for green and false for red.
	
### Emergency vehicle detection
   A separate sensor that will transmit the override command for ambulances, police vehicles and other emergency-related situations.

### Prerequisites

 - Software:
   - Windows or Linux operating system
- Hardware:
   - Intel 6th Generation and above Generation based processors
   - Minimum 8 GB RAM
- TOOLS
   - Dockers
   - Google Map service
   - Intel OpenVINO
   - OpenCV

### Results
   The following screenshots is the result of our project after using different videos, captured with different cameras with different angles:

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data1.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data2.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data3.jpeg)

![Image of Result_Data](https://github.com/Intel-Edge-AI-Scholars/SmartTrafficControl/blob/master/Result_Data/data4.jpeg)

# **WORKING MECHANISM**
   To run the project we need a single edge device which will be working with one embedded signal system. The project is basically designed to work on edge device systems. which is connected on two areas, one is towards camera and second is towards signal. From there it will take input and the output will be displayed in the form of signals. In the input it will be the vehicles' captured by the cameras. Anywhere on the road the car is presented it will move the lights towards that end. We also used sensors and cameras to improve the efficiency of the traffic control with little human intervention required. 
  This all mechanism follows edge application. Our model is deployed on edge applications and working on edge mechanisms as well. All of the project is on edge but if there may be any issue then we resolve those issues through cloud computing mechanisms. All the issues will be solved and then it will deploy on edge using Machine Learning Algorithms. We shall inter-connect all the devices of the project to the cloud so, when we face any error all the problems will be customized through cloud as we all are inter-connected so this may easily help in resolving any problem any time.

# **FUTURE WORKS**
   - Traffic Signal Violation Detection:
	Checks for any vehicle passing through the sensors and cameras if they have violated the signal rules.
   - Licenses Plate Detection:
	Checks the license plate of a vehicle, verify its authenticity and get its information from the national database center if required.

### Conclusion
   The main objective of the project is to develop a system of traffic flow where we would present our ideas more precisely about traffic control. We have worked on the openVINO toolkit and put all our basic knowledge and the course content materials to use in order for us to implement Edge AI Model Deployment knowledge so we could deliver a good project. Thanks to our member’s valuable contribution we have been successful in achieving the desired results. In the future, we look forward to converting this model into OpenVINO as well.  
   These projects are very common nowadays as lots of cities across the globe are working in these areas and they have delivered the transparent volatile system to the market which will provide efficiency to the traffic flow of the city. It is so helpful on weekends as well as more people go for outings with their family members so they need a smooth traffic system to go to their enjoyment place without any wastage of time and without any stress

### Members
   - Muhammad Danial   
   - Syed Muhammad Masab Hashmi 
   - Muhammad Ahwar   
   - Umair Alam 
   - Qasim Hasan   
   - Muhammad Ali 
   - Hanzala Ejaz   
   - Asad-Ur-Rahman 
   - Muhammad Asim   
   - Haseeb Ahmed Khan

Star this Repo,to encourages the team-members :smiley:

:+1: This PROJECT looks great - It's ready for the SHOWCASE! :shipit:
