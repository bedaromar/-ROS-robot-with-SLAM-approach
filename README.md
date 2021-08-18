# -ROS-robot-with-SLAM-approach

[task3.pdf](https://github.com/bedaromar/-ROS-robot-with-SLAM-approach/files/7003834/task3.pdf)

I suggest to see the task through the PDF file attached above..

This is my third task in Robotics and AI department at SMART METHODS summer training, And In this file I'll explain the steps for using robot arm in ROS.

## Detailed Steps:

1- I used the codes from Amg0z account https://github.com/Amg0z/Task-4

![Circuit Diagram](https://github.com/bedaromar/-ROS-robot-with-SLAM-approach/blob/main/screenshot/Screenshot%201443-01-10%20at%2004.34.57.png)

2- Install the Robot

 -  `$ sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation`
 -  `$ cd ~/catkin_ws/src`
 -  `$ git clone https://github.com/bedaromar/Task-4`
 -  `$ cd ..`
 -  `$ catkin_make`
 -  `$ source ~/catkin_ws/devel/setup.bash then I run it by this command`
 -  `$ roslaunch warehouse_simulation warehouse_simulation.launch`
 
![Circuit Diagram](https://github.com/bedaromar/-ROS-robot-with-SLAM-approach/blob/main/screenshot/Screenshot%201443-01-10%20at%2004.35.14.png)

3- Draw the map and save it
-  `$ rosrun map_server map_saver -f ~/map `
![Circuit Diagram](https://github.com/bedaromar/-ROS-robot-with-SLAM-approach/blob/main/screenshot/Screenshot%201443-01-10%20at%2004.35.25.png)


And finally the map has been successfully drawn.
