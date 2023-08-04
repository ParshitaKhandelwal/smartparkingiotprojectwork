# smartparkingiotprojectwork

                                                              **Problem Statement**
                                                              
As the population has been increasing tremendously, vehicular traffic and its parking has become an issue of great concern. In public places where there are many visitors, a lot of time is wasted for searching parking slots. Also, a lot of manual labour is required to look after the existing parking arrangement. Moreover, there is no way of knowing whether a vacant parking space is available or not. The smart parking system is going to be implemented in several countries. In India, this type of parking system is most likely to be implemented in Bangalore in the near future.

                                                                **Proposed Solution**
                                                                
The given automatic parking system which is safe, speedy, user-friendly and cost-effective includes the following features:

a.Automated parking system without any manual labour
b.Simultaneous operations on different floors for car parking
c.Multiple entry and exit points
d.Pre-booking of parking slots through a mobile App
e.Categorization of vehicles by size and weight based on which the driver will be given a place to park the car. In this way, heavy and larger vehicles can be given a parking space on the Ground floor for convenience.

                                                          **Basic Components and Softwares used**

a.STM32103C to be used as the microcontroller
b.Ultrasonic Sensors to detect the presence of a vehicle near entry or exit
c.IR Sensors to detect occupancy in each parking space
d.Servo motors to be used as shafts
e.Arduino IDE for firmware development
f.Thunkable Classic for Android App development
g.Anaconda-OpenCV Python for Image Processing and weight detection
h.LCD Nokia 5110

                                                                    **Working**
                                                                    
When a vehicle arrives in front of UV sensor it sends a signal to servo motor which rotates 90 degrees up and allows the car to enter inside. Once the capacity of the system is full no more vehicle is allowed inside.The exit and entry system work simultaneously with the help of a counter which increments or decrements as a vehicle enters or leaves the parking slot. The IR sensors help to identify filled and empty spaces.
