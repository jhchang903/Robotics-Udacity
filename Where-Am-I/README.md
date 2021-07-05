# Project3
Design a robot that chases a white ball and simulate in ROS.


## Clone directory
```
git clone https://github.com/jhchang903/Robotics-Udacity.git
```


## Create a catkin workspace and initialize it
```
mkdir catkin_ws/src
cd catkin_ws/src
catkin_init_workspace
cd ..
cd ..
mv Robotics-Udacity/Where-Am-I/{my_robot,pgm_map_creator,teleop_twist_keyboard} catkin_ws/src
```


## Compile the packages
```
cd catkin_ws
catkin_make
```

## Launch my_robot
```
cd catkin_ws
source devel/setup.bash
roslauch my_robot world.launch
```

##  Launch ball_chaser 
**Open a new terminal**
```
cd catkin_ws
source devel/setup.bash
roslaunch my_robot amcl.launch
```

##  Simulation in ROS
<img src="https://github.com/jhchang903/Project2/blob/master/ros.gif" width="700">
