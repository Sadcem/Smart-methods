# ROS Noetic And ROS2 Foxy Installation #


## To Install ROS Noetic for Ubuntu 20.04 :
1 - Setup sources.list:

``` sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' ```


2 - Set up keys:

``` sudo apt install curl: # if you haven't already installed curl ```
```curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add - ```


3 - Make sure your Debian package index is up-to-date:

``` sudo apt update ```


4 - For the Recommended Complete Bundle use:

``` sudo apt install ros-desktop-full ```


5 - Environment setup *Use this script in every terminal you use ROS*

``` source /opt/ros/noetic/setup.bash ```



6 - Use this Script so everytime you type roscore in a new terminal it starts using ROS Noetic : ``` echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc ```


Just like this :


![Screenshot 2024-07-29 204800](https://github.com/user-attachments/assets/2ddaa87e-7e06-4c3b-8326-6f5c6c375d33)





# ROS2 Foxy Installation #


## To Install ROS2 Foxy for Ubuntu 20.04

1 - First Set Locale with these commands and run each one individually:

``` locale  # check for UTF-8 ```

``` sudo apt update && sudo apt install locales ```
```sudo locale-gen en_US en_US.UTF-8```
``` sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8 ```
``` export LANG=en_US.UTF-8```

``` locale  # verify settings ```


2 - Setup sources and enable Ubuntu Universe repository:

``` sudo apt install software-properties-common```
``` sudo add-apt-repository universe ```


3 - Add the ROS 2 GPG key with apt

``` sudo apt update && sudo apt install curl -y```
``` sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg ```


4 - Now Update the apt repository :

``` sudo apt update ```


5 - Ensure that the system is up to date before installing new packages

``` sudo apt upgrade ```


6 - Desktop Install: ROS, RViz, demos, tutorials

``` sudo apt install ros-foxy-desktop python3-argcomplete ```


7 - ROS-Base Install :

``` sudo apt install ros-foxy-ros-base python3-argcomplete ```


8 - Development tools: Compilers and other tools to build ROS packages

``` sudo apt install ros-dev-tools ```


## Enviroment setup ##

- Frist Open a new termnal and enter this command :
  
``` source /opt/ros/foxy/setup.bash ```

- Second Type

  ``` gedit ~/.bashrc ```

  ![Screenshot 2024-08-01 071801](https://github.com/user-attachments/assets/2e450adb-0356-4cf5-96cd-f0716f48cc6e)


- You will get this page the type ``` source /opt/ros/foxy/setup.bash ``` again at the last of the page " it's highlighted in orange"
 then click save and close the page when you are done

![Screenshot 2024-08-01 071842](https://github.com/user-attachments/assets/e67d6090-439e-4bf7-bb4a-583d3fc5e53d)


- Now everytime you type ros2 run you will able to able to use ros2

  ![Screenshot 2024-08-01 071929](https://github.com/user-attachments/assets/6ac7c557-c2bd-4d91-b2ef-b7d61903288b)



## The end



