# SPAM-Bot #

The project is build using the Arduino UNO and Arduino duemilanove/ATmega328p boards. It makes use of continuous rotational servos for the wheels of the robot and positional rotational motors for the robot arm and gripper. IR sensors are used to detect and follow the navigational path. A Sonar sensor is used to identify the payloads across the map. A Rasberry Pi connected to a normal Webcam is used to capture the payload key and process it.

### What is this repository for? ###

This is an Autonomous Robot designed to navigate across a map and collect payloads distributed at various points. These payloads are delivered at the other end of the map in a sorted order (adjacent to each other with only the last payload on top if the previous one). The sorting is done according to a barcode number printed on each face of the payload.

### How do I get set up? ###

* The Fully Rotational Servos used for the wheels are connected to the Arduino UNO boards pins 13 and 12.
* The Servos controlling the Arm & Gripper motion are connected to pins 10 to 13 of the Duemilanove board.
* The Web Camera is connected to the Rasberry Pi board
* The Arduino boards and the Rasberry use I2C for communication
* The sonar is connected the pins 9 & 10 of the Arduino UNO board
* The Rasberry Pi runs OpenCV to process the captured images


### Contribution guidelines ###

* This was a private project of four students for a Robotics competition. However, we thought of letting other people use this and contribute. So, feel free to download the source, do the configuration and test it for your own projects, and contribute if you can.

### Who do I talk to? ###

* Any of the Repo Admins of **S** *(habir)* - **P** *(raneeth)* - **A** *(nushanga)* - **M** *(ilan)* - BOT

Shabir     : shabir.tck@gmail.com
Praneeth     : gnomez.grave@gmail.com
Madura (Anushanga)     : Madura.x86@gmail.com
Milan     : milanharindu.ucsc@gmail.com

Visit the following link for the full updated documentation.

https://docs.google.com/document/d/10o8Z-cw7VPhWjj2O9r8bFGVNF2Bobu37ml4c4lm89bA/
