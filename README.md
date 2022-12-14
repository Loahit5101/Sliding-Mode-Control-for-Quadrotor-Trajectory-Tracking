# Sliding Mode-Control for Quadrator Trajectory Tracking

Robust Trajectory Tracking for Quadrotor UAVs using Sliding Mode Control - Robot Control course Project, WPI




https://user-images.githubusercontent.com/55102632/207740705-ffa681c8-7b36-4fee-b4b7-5d7635f6ed74.mp4





## Setup
 Follow the below commands 
```
mkdir -p ~/rbe502_project/src
cd ~/rbe502_project/src
catkin_init_workspace 
cd ~/rbe502_project
catkin init
cd ~/rbe502_project/src
git clone -b dev/ros-noetic https://github.com/gsilano/CrazyS.git
git clone -b med18_gazebo9 https://github.com/gsilano/mav_comm.git
git clone https://github.com/Loahit5101/Sliding-Mode-Control-for-Quadrator-Trajectory-Tracking.git
```
## Running the conroller
```
rosrun control controller.py
```
## Tracked Trajectory

Desired waypoints: (0,0,0)->(0,0,1)->(1,0,1)->(1,1,1)->(0,1,1)->(0,0,1)

![WhatsApp Image 2022-12-14 at 18 36 15](https://user-images.githubusercontent.com/55102632/207740761-de53e86f-b170-4325-89af-d95bffbbfb56.jpeg)





