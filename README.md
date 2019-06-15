# bwRobotRrmSimple
The results of the moveit in rviz plan are sent to gazebo to go.
This project is mainly to learn ROS about the movet of the robotic arm,and The results of the moveit in rviz plan are sent to gazebo to go.

In the next few steps, you can use this feature pack to view the demo effect.

1. First you should make sure you have ros installed.you can follow this [Ros](http://wiki.ros.org/kinetic/Installation/Ubuntu).

2.Then you need to install moveit and the dependencies it needs

sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-gazebo* ros-kinetic-moveit* ros-kinetic-robotis-math ros-kineticindustrial-core

3. Than you can clone this project to your Workspace src.
git clone https://github.com/Sunweijun333/bwRobotRrmSimple.git

4.Compile this project
 catkin_make
5 You can open the model and plan the action in rviz as follows.
 roslaunch bw_arm_description bw_robot_arm_rviz.launch
6 you also open the model in gazebo as follows
 roslaunch bw_arm_gazebo bw_arm_world.launch
7 you can realize the goal for the results of the moveit in rviz plan are sent to gazebo to go as follows.
 roslaunch bw_arm_gazebo bw_arm_bringup_moveit.launch
 
 Last thank you for your visiting!
