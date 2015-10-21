# Creation & Computation Research Project on Volume by United Visual Artist
### Arduino slave controller for Mozzi 

For our research project in our Creation & Computation class were tasked to do a presentation and prototype as a proof of concept for the installation by United Visual Artists called Volume.

To prototype this installation we made use of the following Arduino Libraries:
* [Mozzi](sensorium.github.io/Mozzi/)
* [UltrasonicSensor](http://playground.arduino.cc/Main/UltrasonicSensor)
* [ShiftOut](https://www.arduino.cc/en/Tutorial/ShiftOut) using the 74HC595 integrated chip
* [Arduino to Arduino serial communication](http://robotic-controls.com/learn/arduino/arduino-arduino-serial-communication)

Because of the dependencies and that Mozzi overwrites some default Arduino functions we needed to use a secondary Arduino to run only Mozzi.

The first Arduino which is used to control and run the LED matrix and Sonar Sensor has its own repo [here](https://github.com/jshaw/cc-research-project-uva-mozzi). 

We also have a post on the Creation & Computation class [blog titles Research Project: Volume by United Visual Artist](http://blog.ocad.ca/wordpress/digf6037-fw201502-01/2015/10/research-project-volume-by-united-visual-artist/).
