# Navigation, Path Planning for Jackal
Jackal livox navigation is a ROS package for Navigation, Path Planning using Jackal UGV

## Requirements
Ubuntu version: Ubuntu 20.04  

ROS version: ROS noetic  
https://wiki.ros.org/noetic/Installation/Ubuntu  

**We used Livox MID-360 LiDAR sensor**  
**must install livox ros driver**  
https://github.com/Livox-SDK/livox_ros_driver2

## How to run
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
rosrun rviz rv
```
