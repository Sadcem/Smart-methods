# ROS Installation and Configuration #

## To Install Robot Operating System for Ubuntu 20.04 :
1 - Setup sources.list: ``` sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' ```


2 - Set up keys ``` sudo apt install curl: # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add - ```


3 - Make sure your Debian package index is up-to-date: ``` sudo apt update ```


4 - For the Recommended Complete Bundle use: ``` sudo apt install ros-desktop-full ```


5 - Environment setup: ``` source /opt/ros/noetic/setup.bash
Use this script in every terminal you use ROS ```


6 - Use this Script so everytime you type roscore in a new terminal it starts using ROS Noetic : ``` echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc ```


Just like this :


![Screenshot 2024-07-29 204800](https://github.com/user-attachments/assets/2ddaa87e-7e06-4c3b-8326-6f5c6c375d33)




