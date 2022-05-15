# WIPER_CONTROL_SYSTEM

### Abstraction
 This is an era of automation where it is broadly 
defined as replacement of manual effort by mechanical power 
in all degrees of automation. Now a day’s almost all the 
automobile vehicles are being atomized in order to reduce 
human efforts. The AUTOMATIC RAIN OPERATED WIPER 
system is a fully automation project. This is a genuine project 
which is designed for automobile vehicles and is fully equipped 
by sensor circuit and wiper motor. This project work includes 
design and development of a control system based on 
electronically controlled automotive rain operated motor called 
AUTOMATIC RAIN OPERATED WIPER.

### INTRODUCTION
A Windscreen or windshield wiper is a device used to 
remove rain and debris from a windscreen or windshield. 
Almost all motor vehicles motor, including trains, aircraft 
and watercraft, are equipped with such wipers, which are 
usually a legal requirement. The first windshield wipers 
were brushes. Inventor J. H. Apjohn came up with a method 
of moving two brushes reciprocate on a vertical plate glass 
windshield in 1903. In the same year, Mary Anderson 
devised a swinging arm that swept rain off the windshield 
when the driver moved a lever located inside the car. 

![STRUCTURAL DAIGRAM OF WIPER CONTROL SYTEM](https://user-images.githubusercontent.com/91199828/168464173-f11556ec-c589-4563-afd5-5487834bb754.png)

Anderson patented her invention of the mechanical 
windshield wiper in 1905, and it became standard equipment 
by 1913. Electric motors were not used yet to power 
automobile essentials or accessories. Without another power 
source, a driver had to use one hand to move the lever. 
Rubber strips replaced brushes as the cleaning tools on 
wipers in 1905. Unfortunately, the hazardous need for 
drivers to wipe windshields while driving was not 
eliminated until 1917. The solution was to use an electric 
motor to move a single wiper with a long rubber blade back 
and forth. Hawaiian dentist Dr. Ormand Wall invented the 
automatic wiper by placing an electric motor in the top 
center of the windshield so the wiper arced down over the 
hood of the car in a semi-circular or rainbow shape. Wipers 
were one of the first electrical devices in automobiles after 
the electric starter was developed in 1912. Most wipers on 
cars before 1930 were paired and hung down from the top of 
the windshield. They were moved to the base of the 
windshield as electrical systems became more complicated. 
In 1989 Hideki Kajioka, etal. [1] in their paper an automatic 
wiper which detects rain drops with an optical rain sensor 
was developed. This automatic wiper is implemented by 
combining an existing wiper system with a sensor and 
controller. In 1992, G.K.Ananthasuresh, etal. [2] developed 
a general procedure for synthesizing the rack and pinion mechanism up to seven precision conditions. In 2011, Hong 
Ching Wah[3] invented an operating the car wiper 
automatically when raindrop is sensed. A fluid sensor is 
comprised and mounted on the outer part of the car 
windshield to detect raindrop. Renault Safety Manual [4] 
gives Automatic activation of the windscreen wipers is 
controlled by an infrared sensor which detects the presence 
of water droplets on the wind screen by the modifications in 
reflection that they induce.

![MODEL OF WIPER CONTROL SYSTEM1](https://user-images.githubusercontent.com/91199828/168464229-0c1b1e8b-98d0-423a-b48a-8427e9bd2a91.gif)

I would like to point out that, despite the fact that practically everything about this design has previously been defined, there are still several types of enhancements that may be implemented to make it even more convenient. In terms of efficiency and cost effectiveness, the project that we have developed and presented is pretty effective. In comparison to the optical sensor, it has significant advantages in that it can accommodate all of the design parameters as well as the needs of the average person. This project can benefit from the addition of a speed-controlling mechanism, which will allow it to operate in accordance with the intensity and speed of the water flowing through the sensor. The fundamental manoeuvring is done merely to make it more cost-effective and reliable in the long run. The idea i have been implemented is completly in working condition these can be used in any type of cars.We can also make this wiper system automatic by adding sensors for rain water falling on the wind shiled,dust resistance sensor,etc.So,there is no need to control the wiper system manually while driving the car.It can be more convinient we add the additional features to the wiper system and it can be done in near future.People around the world still working on this project so that we can make a system that works requires less human intervention.

![Simulation Design](https://user-images.githubusercontent.com/91199828/168464346-5e4e4ebd-dd3c-4b6b-9abf-241a90ede547.png)

### Makefile
CC= arm-none-eabi-gcc

MACH=cortex-m4

CFLAGS=-c -mcpu=$(MACH) -mthumb -std=gnu11 -Wall -O0

LDFLAGS= -nostdlib -T stm32_ls.ld

all:main.o MyStm32f407xx_gpio_driver.o stm32_startup.o finalled.elf

main.o:main.c
	$(CC) $(CFLAGS) -o $@ $^

MyStm32f407xx_gpio_driver.o:MyStm32f407xx_gpio_driver.c
	$(CC) $(CFLAGS) -o $@ $^

stm32_startup.o:stm32_startup.c
	$(CC) $(CFLAGS) -o $@ $^

finalled.elf:main.o MyStm32f407xx_gpio_driver.o stm32_startup.o
	$(CC) $(LDFLAGS) -o $@ $^		
	
clean:
	rm -rf *.o *.elf
  
  ### WORKING OF RAIN OPERATED WIPER
The battery supplies the power to the sensor as well as rain 
operated motor. Wiper motor is automatically ON during the 
time of rainfall. The senor is fixed in the vehicle glass. The 
conductive (Touch) sensor is used in this project. It senses 
the rainfall and giving control signal to the control unit. The 
control unit activates the wiper motor automatically.

### Flow chart

![FLOW CHART1](https://user-images.githubusercontent.com/91199828/168464539-592fed10-dec4-4ab8-8e0e-40afc7436460.png)

### output images

![Button pressed once again for two seconds car is on ACC mode that means car turned off](https://user-images.githubusercontent.com/91199828/168464618-fe49c362-60ad-4e33-8665-2d8fdc54b279.png)
![Button pressed for second time wiper turned on](https://user-images.githubusercontent.com/91199828/168464582-6c296e6b-6688-40bf-8915-57e9a6deff9e.png)
![Button pressed for thrd time wiper turned off](https://user-images.githubusercontent.com/91199828/168464588-024150a8-6bde-4a0e-8f66-bbf21b601f8b.png)

### Advantages

➨It helps in saving money by switching off the irrigation system when it rains. This saves money by cutting off bills on electricity consumption.

➨It extends life of rain sensor based systems such as car wiper, irrigation systems by running them only when it is necessary.

➨Rain sensors help save water during rain events and hence water is available during summer and emergency applications such as firefighting etc.

➨Operating principle is very easy.

➨It consumes less power for operation.

➨Installation of rain sensor based systems are very much simple.

➨Individual rain sensor costs very less.

### CONCLUSION AND FUTURE SCOPE
 And finally we conclude that, the wind screen 
wiper which we had fabricated with the main theme of 
maintaining automation by using conductive sensor to the 
required extent is a modification to the existing wind screen 
wiper which were been using in the four wheelers.

 And therefore, implementation of this modified wind 
screen wiper helps in reducing human effort, free from wear 
adjustment and operating principle is very easy which were 
the problems being faced with the existing wind screen 
wiper.

Presently the mode of power source used in our 
project is a battery which is a replaceable power source. 
Here we have used the battery which is a non-conventional 
source of power, keeping the scope of resources in mind this 
can be easily replaced by the conventional power sources 
like solar panels etc.

### REFERENCES
1. Hideki Kajioka, Keiji Fujimura, Yasuhiro Fujita, “Automatic 
Wiper controller using Optical rain sensor”, Fujitsu Ten Tech. 
Journal, No.2, 1989

2. G.K.Ananthasuresh, S.N.Kramer, “Kinematic synthesis and 
analysis of the rack and Pinion Multipurpose Mechanism”, 
ASME journal, 428 / Vol. 114, SEPTEMBER 1992.

3. Hong Ching Wah, “AUTOMATIC RAIN OPERATED 
WIPER IN A CAR”, Engineering Mechtronics, No.5, 2011.
4. Renault Safety Manual, “Automated headlights and 
windscreen-wiper activation”. 

5. “THEORY OF MACHINES”, S.S RATTAN, Third Edition, 
Tata McGraw Hill Education Pvt Ltd, 2009.
6. “THEORY OF MACHINES” BY R.S.KHURMI IN 1976 
S.CHAND & COMPANY LTD. 

7. ”ENGINEERING CIRCUIT ANALYSIS” BY WILLIAM 
H.Hayt, Jr.,Jack E.Kemmerly, Steven M.Durbin IN 2002 BY 
TATA MCGRAW-HILL PUBLISHING COMPANY 
LIMITED. 

8. Hunt, K. H., Kinematic Geometry of Mechanisms, Oxford 
Engineering Science Series, 1979.

9. ”ELECTRICAL OPERATING CIRCUIT FOR VEHICLE 
WINDSCREEN WIPERS”. United States Patent and 
Trademark Office.

10. “LINEAR IC APPLICATIONS” by U.A Bakshi,A.P Godse in 
2009 Technical publications.

  
  

