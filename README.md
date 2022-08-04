# task5_mapping
# 1install ROS
# 2install Gazebo
# Default installation: one-liner
## install [ curl -sSL http://get.gazebosim.org | sh ] 
### Run [ gazebo] 
![Screenshot from 2022-08-04 17-23-28](https://user-images.githubusercontent.com/95400206/182911066-37ef2e03-b60d-4968-9609-c5dbb5c9e33b.png)
## Quick Start Guide
### Install Dependent ROS Packages
**$ sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \
  ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \
  ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \
  ros-noetic-rosserial-python ros-noetic-rosserial-client \
  ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \
  ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \
  ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \
  ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers**
  ### Install TurtleBot3 Packages
  **$ sudo apt install ros-noetic-dynamixel-sdk
$ sudo apt install ros-noetic-turtlebot3-msgs
$ sudo apt install ros-noetic-turtlebot3**
### Launch the Navigation
**$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml**
![Final](https://user-images.githubusercontent.com/95400206/182912150-6dcbb071-8e2f-49e9-9717-52e68bb8f40a.jpeg)

