# Radar-System-using-Arduino-Ultrasonic-Sensor

# INTRODUCTION
We know everything produces sound wave just by existence and effect flow of air around them with their natural frequency. These frequencies are beyond hearing range of humans. Wave of frequency range of 20000hz and thereabouts are called ultra-sonic wave and these waves can be detected by an ultrasonic sensor which helps us to get various knowledge. 
An Ultrasonic detector usually has a transducer which convert sound energy into electrical energy and electrical energy into sound energy. They are used for measuring object position and orientation, collision avoidance system, surveillance system etc. 
Ultrasonic technology provide relief from problem such as linear measurement problem, as it allows user to get non-contact measurements in this way distance between object and its speed etc can me easily measured.  
Speed of travel of sound wave depends upon square root of ratio between medium density and stiffness. Also, property of speed of sound can also be changed by natural environment condition like temperature. 
So basically, an ultrasonic sensor sends ultrasonic waves which travels in air and gets reflected after striking any object. By studying the property of reflected wave, we can get knowledge about objects distance, position, speed etc. 
A processing software and an Arduino software is used with hardware system for detection of objects various parameters. 
One of the most common application of ultra-sonic sensor is range finding. It is also called as sonar which is same as radar in which ultrasonic sound is directed at a particular direction and if there is any object in its path it strikes it and gets reflected back and after calculation time taken to come back we can determine distance of object.  in real life this method is used by bats. 
 
# DESIGN IMPLEMENTATION OF RADAR SYSTEM 
The figure shown below shows the development life cycle of Radar project which involves various step such as design of different components, their testing, their implementation and implementation of entire system and their testing. These steps can be enumerated into following stages 
a)	Hardware System Design. 
b)	Hardware Circuit Design. 
c)	Hardware System implementation. 
d)	Hardware unit testing. 
e)	GUI System Design. 
f)	GUI System Implementation. 
g)	GUI unit testing. 
h)	Entire system integration. 
i)	Entire system testing. 

# Hardware system design
Hardware system consist of basically 3 components named as Arduino, servo-motor, and ultra-sonic sensor. Ultrasonic sensor is mounded upon a servo motor which helps it to move and provide it a turning mechanism. Both ultrasonic sensor and servo motor are controlled and powered by Arduino. As given in above figure 2 we can see both ultrasonic sensor and servo motor is powered by Arduino. 
 
# System circuit design
Figure shows hardware system design which was designed using fritzing environment. It shows the connection of different electronics components. In the figure triggering pins of ultrasonic sensor is connected to D8 pin of Arduino, control line of servo motor is connected to D6 pin of Arduino and D7 pin of Arduino is connected to echo pin. VCC pins of servo motor and ultrasonic sensor is connected to 5V pin of Arduino while ground pin of Arduino is connected to ground pin of both servo motor and ultra-sonic sensor. 

# WORKING 
The aim of this project is to calculate the distance position and speed of the object placed at some distance from the sensor. Ultrasonic sensor sends the ultrasonic wave in different directions by rotating with help of servo motor. This wave travels in air and gets reflected back after striking some object. This wave is again sensed by the sensor and its characteristics is analysed and output is displayed in screen showing parameters such as distance and position of object. 
Arduino IDE is used to write code and upload coding in Arduino and helps us to sense position of servo motor and posting it to the serial port along with the distance of the nearest object in its path. The output of sensor is displayed with the help of processing software to give final output in display screen. 
  
# Ultrasonic sensor 
An ultrasonic sensor works similar as of sonar. It can measure distance of object by sending sound waves. Sound waves are send at a specific frequency at a specific direction and listen for sound wave to come back. time taken by sound wave to come back helps us to determine distance of object. 

# Servo motor 
A servomotor is a rotary actuator that allows for precise control of angular position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback. It also requires a relatively sophisticated controller, often a dedicated module designed specifically for use with servomotors. Servomotors are not a different class of motor, on the basis of fundamental operating principle, but uses servomechanism to achieve closed loop control with a generic open loop motor. Servomotors are used in applications such as robotics, CNC machinery or automated manufacturing. 
  
# Arduino  
The Arduino is an open source electronics platform based on easy to use hardware and software. The open source Arduino software makes it easy to write code and upload it to the board. It runs on Windows, Mac OS X and Linux. The environment is written in java and based on processing and other open source software. This software can be used with any Arduino board. The Arduino software IDE contains a text editor for writing code, a message area, a text console, a toolbar with buttons for common function. It connects to Arduino and Genuino hardware t+o upload programs and communicate with them. Program written using Arduino software are called sketches.

# ADVANTAGES 
1. Radar procurable value is very low
2. Working and maintenance value is low. 
3.	Distance active resolution is high  
4.	Radar’s jam is troublesome 
5.	It can work in any place 
6.	NASA uses radio detection and ranging to map the world and alternative plants 7. Activity gets updated in conclusion    
 
# Conclusion 
In this paper a system radar system was designed with the help of Arduino, servomotor and ultrasonic sensor which can detect the position, distance of obstacle which comes in its way and converts it into visually representable form. 
This system can be used in robotics for object detection and avoidance system or can also be used for intrusion detection for location sizes.  Range of the system depends upon type of ultra-sonic sensor used. We used HC-SR04 sensor which range from 2 to 40 cm. 
 
# REFERENCES 
[1]	G. Bhor, P. Bhandari, R. Ghodekar and S. Deshmukh, "Mini Radar," International Journal of Technical Research and Applications, pp. 68-71, 2016. 
[2]	D. B. Kadam, Y. B. Patil, K. V. Chougale and. S. S. Perdeshi, "Arduino Based Moving Radar System," International Journal of Innovative Studies in Sciences and Engineering Technology (IJISSET), vol. 3, no. 4, pp. 23-27,2017. 
[3]	T. P. Rajan, K. K. Jithin, K. S. Hareesh, C. A. Habeeburahman and. A. Jithin, "Range Detection based on Ultrasonic Principle," International Journal of Advanced Research in Electrical, Electronics and Instrumentation Engineering, vol. 3, no. 2, pp. 7638-7643, 2014. 
[4]	P. S. Abhay,. S. K. Akhilesh, P. Amrit and Kriti, "A Review on Ultrasonic Radar Sensor for Security system," Journal ofEmerging Technologies and Innovative Research (JETIR), pp.137-140, 2016. 
[5]	P. P. Arun, M. A. Sudhakar, P. MeghaSunil and S. S. Balaji,"Ultrasonic Distance Meter," SVERIAN Scientific, pp. 1-4,2015. [6] O. V. Amondi, "Collision Avoidance System," The University Of Nairobi, 2009. 
[7]	Shamsul A., Tajrian M., “Design of an Ultrasonic Distance Meter”, International Journal of Scientific & Engineering Research, pp. 110, March 2013. 
[8]	U. Papa, G. D. Core, “Design of sonar sensor model for safe landing of an UAV”, Proc. IEEE Metrol. Aerosp., pp. 346-350, Jun. 2015. 
[9]	Abbay P., Akhilesh S., Amrit P., and Prof Kriti, “A Review on Ultrasonic Radar Sensor for Security system”, Journal of Emerging Technologies and Innovative Research (JETIR),April 2016. 
[10]	Babu Varghese, “Collision Avoidance System in Heavy Traffic & Blind spot Assist Using Ultrasonic Sensor”,International Journal of Computer Science and Engineering Communications-IJCSEC. Vol. 2, Isuue 1, February, 2014 ISSN: 2347-8586. 
[11]	S. Bharambe, R. Thakker, H. Patil, K. M. Bhurchandi,“Substitute eyes for blind with navigator using android”, Proc.Texas Instrum. India Edu. Conf. (TIIEC), pp. 38-43, Apr.2013. 
[12]	D. Sunehra, A. Bano, S. Yandrathi, "Remote monitoring and control of a mobile robot system with obstacle avoidance               capability", Proc. Int. Conf Adv. Comput. Commun. Inf.(ICACCI), pp. 1803-1809, Aug. 2015. 
[13]	http://www.instructables.com/id/ ATMega328-using-Arduino-/  
[14]	Hauptmann, Peter, Niels Hoppe, and Alf Püttmer. "Application of inaudible sensors within the method trade." activity Science and Technology thirteen.8 (2002): R73.  
[15]	Idris, M. Y. I., et al. "Parking system utilizing wireless detector network and inaudible detector." data Technology Journal eight.2 (2009): 138-146. [11]http://www.radomes.org/museum/photos/equip/ANSPS17.jpg [16]http://www.wired.com/dangerroom/2011/07/ suicide-bombers-from-100-yards/ [17]http://upload.wikimedia.org/wikipedia/commons/Radaraccumulationseng.png 
[16]	http://arduino.cc/en/Tutorial/BarGraph/  
[17]	J.G .Proakis, “Digital Comm.”, fourth edition. NY: McGraw- Hill, 2001.  [18] R.BaraniukandP.Steeghs,  
[19] “Compressive radio detection and ranging imaging” in IEEE  [20] Wikipedia 
