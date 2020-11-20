Three-wheel Omnidirectional Robot 
==============================

A ROS/Gazebo omnibot simulator based on yangwei's model. Joint names are modified to be compaitable with ROS melodic.

To use:
	
	$ cd catkin_ws/src
	$ git clone https://github.com/Shervina-lim/omni_simulator.git 
	$ catkin_make
	
To start the simulator:

	$ roslaunch omni_gazebo omnibase.launch

To move the robot, publish control commands to ROS topic /omnibase/cmd_vel.
Alternatively, users can download omni_navigation	
