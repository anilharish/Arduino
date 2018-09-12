###################################################################################################
#				IR Remote TX-RX upto 6 IR sensors				  #
###################################################################################################

Version: 1.4 February, 2018
Author: Anil Harish
Robotics Project : Using 4 sensors (Works upto 6 sensors) visit https://github.com/anilharish/Robotics/Ant_Colony_Particle_Swarm_Optimization
For detials, other Aurdino and Robotics repositories visit https://github.com/anilharish/

PREREQUISITES

1. Windows: Download from Aurdino downloads page and select Windows Installer at https://www.arduino.cc/en/Main/Software
2. Linux/Ubuntu: Follow the instructions on the page https://www.arduino.cc/en/Guide/Linux

INSTALLING

1. Importing .zip file or folder

   a.In the Arduino IDE, navigate to Sketch > Include Library > Add .ZIP Library. At the top of the drop down list, select the option to "Add .ZIP Library''.
   
   b.You will be prompted to select the library you would like to add. Navigate to the .zip file's location and open it.
   
   c.Return to the Sketch > Include Library menu. menu. You should now see the library at the bottom of the drop-down menu. It is ready to be used in your sketch. The zip file will have been expanded in the libraries folder in your Arduino sketches directory.

   d.RESTART Arduino IDE

NOTE:The Library will be available to use in sketches, but with older IDE versions examples for the library will not be exposed in the File > Examples until after the IDE has restarted. 

2. Manually Installing the Library

   a.Close all existing Arduino IDE's or Windows/Arduino IDE instances.
   
   b.Copy the folder IRremote in the “libraries” folder inside your sketchbook.
   NOTE: In Windows default location is /Documents/Arduino/libraries

   b.Start the Arduino Software (IDE), go to Sketch > Include Library. Verify that the library you just added is available in the list.

NOTE: Arduino libraries are managed in three different places: inside the IDE installation folder, inside the core folder and in the libraries folder inside your sketchbook. The way libraries are chosen during compilation is designed to allow the update of libraries present in the distribution. This means that placing a library in the “libraries” folder in your sketchbook overrides the other libraries versions.

LICENSE

GNU LESSER GENERAL PUBLIC LICENSE

COPYRIGHT

Copyright 2009 Ken Shirriff
