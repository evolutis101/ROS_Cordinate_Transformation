# ROS_Cordinate_Transformation

Relative coordinates transdormation of each joint (indicates the relationship between between joints in the form of tree structure)

# lauch demo from terminal 

$sudo apt-get install ros-noetic-turtle-tf
$sudo apt install python-is-python3
$roslaunch turtle_tf turtle_tf_demo.launch
$rosrun turtlesim turtle_teleop_key

# tools 
$sudo apt install ros-noetic-tf2-tool
$rosrun turtlesim tf2_tools views_frames.py

![tree](https://github.com/evolutis101/ROS_Cordinate_Transformation/assets/36013919/e8e393dc-db60-412b-a97a-b80c761e60c7)

you could also used this features in the RVIZ GUI
$rosrun rviz rviz -d 'rospack find turtle_tf' /rviz/turtle_rviz.rviz



