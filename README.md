# Navigation, Path Planning for Jackal
Jackal livox navigation is a ROS package for Navigation, Path Planning using Jackal UGV

## Requirements
Ubuntu version: Ubuntu 20.04  

ROS version: ROS noetic  
https://wiki.ros.org/noetic/Installation/Ubuntu  

Jackal package  
https://github.com/jackal/jackal.git  

**We used Livox MID-360 LiDAR sensor**  
**must install livox ros driver**  
https://github.com/Livox-SDK/livox_ros_driver2  

## Install 
use following commands to install the package

jackal pacakge
```bash
cd ~/catkin_ws/src
git clone https://github.com/jackal/jackal.git 
```
our jackal_livox_navigation package
```bash
git clone https://github.com/Muros-lab/Jackal_livox_navigation

```
install Dependencies
```bash
```

## How to run
**0. add your 2D map in maps file**  

**1. run livox ros driver2**

**2. run jackal_navigation.launch**

```bash
source ~/catkin_ws/devel/setup.bash
source /opt/ros/noetic/setup.bash
```
```bash
roslaunch jackal_livox_navigation jackal_navigation.launch
```

**3. run rviz**
```bash
rosrun rviz rviz
```
