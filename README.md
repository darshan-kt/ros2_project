# ROS2 package with ros2cpp nodes, launch files.

## Environment
* Ubuntu 18.04
* ROS dashing

## Package installation


* Create workspace and install package
  
  ```bash
  mkdir -p ros2_ws/src
  cd ~ros2_ws/src
  git clone https://github.com/darshan-kt/ros2_project.git
  cd ..
  colcon build
  ```

* Running publisher node
  ```bash
  cd ~ros2_ws
  source install/setup.bash
  ros2 run ros2_pkg publisher_node
  ```
* Running publisher node
  ```bash
  cd ~ros2_ws
  source install/setup.bash
  ros2 run ros2_pkg subscriber_node
  ```

* Visualising nodes connecting with rqt_graph
  ```bash
  rqt_graph
  ```
  ![alt text](https://github.com/darshan-kt/ros2_project/blob/master/rqt.png)


## Acknowledgment

Part of the code taken from "A Concise Introduction to Robot Programming with ROS2" text book. 
