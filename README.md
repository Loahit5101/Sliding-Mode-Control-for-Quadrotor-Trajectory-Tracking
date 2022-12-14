# Sliding Mode-Control for Quadrator Trajectory Tracking

Robust Trajectory Tracking for Quadrotor UAVs using Sliding Mode Control - Robot Control course Project, WPI

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




