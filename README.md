# M3_wiper_control_system

This is an era of automation where it is broadly defined as replacement of manual effort by mechanical power in all degrees of automation. Now a day’s almost all the automobile vehicles are being atomized in order to reduce human efforts. The AUTOMATICRAIN OPERATED WIPER system is a fully automation project. This is a genuine project which is designed for automobile vehicles and is fully equipped by sensor circuit and wiper motor. This project work includes design and development of a control system based on electronically controlled automotive rain operated motor called wiper control system.



![pic1](https://user-images.githubusercontent.com/91199828/168461594-0f2c2ae8-4c04-43d0-88ca-12ebdb41b587.jpg)


Today’s car wipers are manual systems that work on the principle of manual switching. So here we propose an automatic wiper system that automatically switches ON on detecting rain and stops when rain stops. Our project brings forward this system to automate the wiper system having no need for manual intervention. For this purpose we use rain sensor along with microcontroller to drive the wiper motor. Our system uses rain sensor to detect rain, this signal is then processed by microcontroller to take the desired action. The rain sensor works on the principle of using water for completing its circuit, so when rain falls on it it’s circuit gets completed and sends out a signal to the microcontroller. The microcontroller now processes this data and controls the motor.This system is equally useful for Aircrafts and a smaller version of this can be used by motor bikers in their helmets so that they can drive easily in rains.
# WORKING MODEL
![MODEL OF WIPER CONTROL SYSTEM1](https://user-images.githubusercontent.com/91199828/168461448-261122ef-a392-4268-b180-ffd1e95c1143.gif) 

Our integrated circuits and reference designs for automotive wiper modules accelerate your design using high-performance motor drivers for brushed or brushless direct current (BLDC) motors to provide intelligent drive capabilities with enhanced diagnostics for robust motion control systems.
# STRUCTURAL DAIGRAM
![STRUCTURAL DAIGRAM OF WIPER CONTROL SYTEM](https://user-images.githubusercontent.com/91199828/168461708-16e3ddc8-b1ca-44c9-8917-82d40a4a357c.png)

Wipers are designed and manufactured to remove water from a windshield. Most automobiles feature two windshield wipers, as well as one on the back window and one on each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the exterior of the automobile. Under the wiper, there are up to six pieces called pressure points or claws, which are little arms. The claws spread the wiper's pressure along the blade's back. The wiper is the beam, and the claws are the suspension components, therefore this is a balancing beam with a suspension system. The claws keep the blade flexed against the windshield, distributing uniform pressure across the blade to clean the glass evenly. Large or strongly curved windshields benefit from more claws because they effectively disperse pressure.

# PCB LAYOUT

![PCB Layout on Eagle](https://user-images.githubusercontent.com/91199828/168461816-bc260342-d2ae-47b3-99ee-28de75f44c25.jpg)

# Design of Wiper Mechanism
Several mechanisms are used for operating the wiper. In 
automobiles most widely used mechanisms for operating 
wiper are rack and pinion and four bar mechanism. And in 
our project 4-bar mechanism is used for operating wiper. It 
converts the rotary motion into oscillating motion. The 
reason behind choosing the 4-bar mechanism is it is simple 
mechanism. In this paper stainless steel bars are used for 
links of 4-bar mechanism, Aluminum is used for the blade 
frame & rubber is for blades. The dimensions of the 4-bar 
mechanism reduced so that it occupies less space. The 
dimensions of links calculated from Grasshoff’s rule. Wiper 
should convert rotary motion of motor into oscillatory 
motion (i.e. crank & Lever mechanism). Case 2 in the table 
is useful for wiper mechanism.

# REQUIREMENT

## HIGH LEVEL
|ID|Discription|Status|
|:-------------|:--------------|:-------------|
|HR_01|Car is in ACC mode|Implemented|
|HR_02|Car is in Ignition mode|Implemented|
|HR_03|Wiper turned on|Implemented|
|HR_04|Wiper turned off|Implemented|

## LOW LEVEL
|ID|Discription|Status|
|:-----------------|:--------------|:------------|
|LR_01|Button pressed ONCE for two seconds - ON LED RED|Implemented|
|LR_02|Button pressed once again times - OFF LED RED|Implemented|
|LR_03|Button pressed two time - ON BLUE,GREEN,ORANGE|Implemented|
|LR_04|Button pressed again for two seconds - OFF ORANGE,GREEN,BLUE|Implemented|

![Model](https://user-images.githubusercontent.com/91199828/168462928-fdb01e3e-5e8c-4ae7-bc81-c07f9e9b3239.jpg)

Wipers are designed and manufactured to remove water from a windshield. Most automobiles feature two windshield wipers, as well as one on the back window and one on each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the exterior of the automobile. Under the wiper, there are up to six pieces called pressure points or claws, which are little arms. The claws spread the wiper's pressure along the blade's back. The wiper is the beam, and the claws are the suspension components, therefore this is a balancing beam with a suspension system. The claws keep the blade flexed against the windshield, distributing uniform pressure across the blade to clean the glass evenly. Large or strongly curved windshields benefit from more claws because they effectively disperse pressure.





