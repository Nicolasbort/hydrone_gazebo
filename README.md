# hydrone_gazebo

Model launch: roslaunch hydrone_gazebo hydrone_world.launch 
Control launch: roslaunch hydrone_control hydrone_control.launch 
Hot to test: rostopic pub /hydrone/joint_aerial_propeller_1_controller/command std_msgs/Float64 "data: 0.5" 
