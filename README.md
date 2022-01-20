# ECSE 476 PS1  
README describes how to use the ```stdr_controller``` ROS package that is built for ```stdr_simulator``` package. Please visit ROS Tutorials page for more information on stdr_simulator. <br>

This package is a simple open loop controller for the simple two dimensional robot. Starting from bottom left corner, open loop controller commands the robot to move to top left corner. This is achieved by publishing messages to ```robot0/cmd_vel``` topic. Launch file is provided to simplify running the package. 

## Preliminary System Requirements 
- Tested on: Ubuntu 18.04 and ROS Melodic
- Have the ```stdr_simulator``` package built and the ROS configured. 
- Clone this package, build, and configure ROS. 
- To build a workspace and configure ROS, run the following commands: <br>
```cd workspace_directory``` <br>
```catkin_make``` <br>
```source devel/setup.bash```

### Use the following launch commands:

## Launching the stdr_controller
To run the stdr_controller, run the command: <br> 
```roslaunch stdr_controller openloopcmd.launch``` <br> 
This will launch the ```stdr_simulator``` and the ```stdr_controller```.

## Arguments 
There are no arguments for the launch files. <br>
