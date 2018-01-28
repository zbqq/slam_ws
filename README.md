# slam_ws
利用mrpt库实现了一下icp_slam、rbpf_slam和amcl定位

如果是indigo版本的话，记得把kinetic换成indigo

1.安装mrpt库

sudo apt-get install ros-kinetic-mrpt-navigation 

sudo apt-get install ros-kinetic-mrpt-slam


2.下载并用catkin_make编译


3.运行amcl定位

source slam_ws/devel/setup.bash

roslaunch slam_ws gazebo.launch

roslaunch slam_ws localizatio.launch


4.安装运行teleop_node,该节点可控制小车移动

sudo apt-get install ros-kinetic-teleop-twist-keyboard 

rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
