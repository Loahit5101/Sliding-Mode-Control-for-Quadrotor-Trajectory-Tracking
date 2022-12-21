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


![Screenshot from 2022-12-21 15-08-00](https://user-images.githubusercontent.com/55102632/208994103-4a8ab2a9-95f5-459f-bfec-c0a7fb8d575a.png)





