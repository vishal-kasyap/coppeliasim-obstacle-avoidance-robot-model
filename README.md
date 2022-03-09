# coppeliasim_obstacle_avoidance_robot_model

This project is a simple Obstacle avoiding mobile robot.

The software used is CoppeliaSim. The link for download is given below.

# https://www.coppeliarobotics.com/downloads

CoppeliaSim Edu gives full access to all the students, teachers, professors, schools and universities

Once downloaded, open the uploaded scene in the software and run the simulation to see the result. 

The robot model is created using the options available in Coppeliasim software.
The detailed reference for doing this is shown in the following youtube video.

# https://www.youtube.com/watch?v=oKOx25SmX58

The concerned algorithm is given as a LUA script to the base link of the robot.
Any changes can be done to the file and the same can be run on simulation.

The summary of the algorithm is very simple.
"At the start of simulation, mobile robot starts moving at a certain speed. If the robot proximity sensor detects any obstacles in the way, it avoids by moving to the right."

The robot, keeps moving to the right if there is an obstacle. The direction of movement can be changed with some minor changes in the LUA script. 
