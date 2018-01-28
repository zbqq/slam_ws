# slam_ws
利用mrpt库实现了一下icp_slam、rbpf_slam和amcl定位

1.安装mrpt库
sudo apt-get install ros-kinetic-mrpt-navigation 
sudo apt-get install ros-kinetic-mrpt-slam

2.下载并用catkin_make编译

3.运行
source slam_ws/devel/setup.bash
roslaunch slam_ws gazebo.launch
roslaunch slam_ws localizatio.launch
