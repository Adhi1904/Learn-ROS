**#Task 1 submission**

You can find the ROS package [here](https://github.com/Adhi1904/Learn-ROS/tree/main/TASK_1/Data)

Creating a catkin workspace
      
      mkdir -p catkin_ws/src
      cd catkin_ws
      source devel/setup.bash

Creating a ROS package
      
      cd catkin_ws/src  
      catkin_create_pkg beginner_tutorials std_msgs rospy roscpp  
      cd catkin_ws
      catkin_make
      source devel/setup.bash

Running turtlesim
      
      roscore  
      rosrun turtlesim turtlesim_node  
      rosrun turtlesim turtle_teleop_key




