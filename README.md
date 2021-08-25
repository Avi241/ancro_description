# ancro_description
Autonomous Navigation and Communication Robot

**Install the Package**

cd ~/catkin_ws/src
git clone https://github.com/Avi241/ancro_description
cd ..
catkin_make 

**Launch the Robot in Gazebo World**

roslaunch ancro_description gazebo.launch

**Run the Robot Teleop Opeartion Script**

rosrun ancro_description robot_teleop.py

**To perform SLAM**

roslaunch ancro_description gmapping.launch

**For Navigation**

roslaunch ancro_description navigation.launch

