# ROS2 package with ros2cpp nodes, launch files.

## Environment
* Ubuntu 18.04
* ROS dashing

## Package installation


* Run the Pure-Pursuit
  * Source the setup.bash
    ```bash
    cd ros_ws
    source devel/setup.bash
    ```
  
  * Launch the Pure-Pursuit node
    ```bash
    roslaunch pure_pursuit pure_pursuit_node.launch
    ```

* Play the rosbag for offline testing
  ```bash
  rosbag play offline_testing.bag
  ```

* Subscribe the ackermann messages from the topic `/cmd_acker`.
  ```xml
  <!--  Demo  -->
  ---
  header: 
    seq: 224
    stamp: 
      secs: 1649337997
      nsecs:  48033928
    frame_id: ''
  drive: 
    steering_angle: 0.270921677351
    steering_angle_velocity: 100.0
    speed: 0.10000000149
    acceleration: 100.0
    jerk: 100.0
  ---
  ```

## Acknowledgment

Part of the code taken from "A Concise Introduction to Robot Programming with ROS2" text book. 

