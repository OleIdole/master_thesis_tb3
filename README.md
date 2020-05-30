# master_thesis_tb3
This repository contains files relevant for the research conducted in a thesis for the degree Master of Engineering (Mechatronic) at University of Wollongong. This repository contains code used on a Turtlebot3 Waffle with ROS. The code is mostly a modified version of the code by ROBOTIS. The original code can be acquired at http://emanual.robotis.com/docs/en/platform/turtlebot3/setup/#setup.

If any of the content is found useful, please give credit to the Author Ole-Martin Hanstveit - https://www.linkedin.com/in/hanstveit/.

Folder "turtlebot3" is a package that belongs inside "\home\.arduino15\packages\OpenCR\hardware\OpenCR\1.4.15\libraries". This package was modified by importing the NewPing library which is found in "/src/sonar". By using this library, the sonar functionality in "/src/turtlebot3/turtlebot3_sensor.cpp" was replaced with the NewPing functions while keeping all the old function names in order to keep it compatible with the rest of the code.
