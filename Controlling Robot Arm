
# Controlling Robot Arm 

- #### First let's create and build a catkin workspace using these commands:
  
``` $ mkdir -p ~/catkin_ws/src ```
``` $ cd ~/catkin_ws/ ```
``` $ catkin_make ```

![Screenshot 2024-08-01 035140](https://github.com/user-attachments/assets/35c0c793-5d99-4811-9acb-9077522d83e3)

- #### Try the command ``` ls ``` if you look in your current directory you should now have a 'build' and 'devel' folder

![Screenshot 2024-08-01 044942](https://github.com/user-attachments/assets/1ad09c90-b7ff-43c1-b36e-9719ca9443b1)


-  #### source your new setup.*sh file:
  ``` source ~/catkin_ws/devel/setup.bash ```

- ##### Run command ``` gedit ~/.bashrc``` and you can see that at the end of the page that apeared the source line we applied earlier


 ``` source ~/catkin_ws/devel/setup.bash ```

 ![Screenshot 2024-08-01 044930](https://github.com/user-attachments/assets/9292e882-8828-40c2-89e0-4fe0ccb02128)




 # Install arduino_robot_arm Package

 - #### first apply command ``` cd src ```  then apply the following command

   ``` sudo apt install git```


![Screenshot 2024-08-01 055142](https://github.com/user-attachments/assets/cc06e1b4-a0de-4800-b108-901c430e70e7)

- #### Use this to link the library with your project
  
``` git clone https://github.com/smart-methods/arduino_robot_arm ```


- #### Next step is going back to ```catkin_ws``` by using ```cd``` command

- #### Then try using:

  ``` rosdep install --from-paths src --ignore-src -r -y ```

  - #### Use command

    ``` sudo apt-get install ros-noetic-moveit ```

    ![Screenshot 2024-08-01 040520](https://github.com/user-attachments/assets/b837606e-d669-43e0-85df-0a6a25422543)


  - #### Use command
 
  - ``` sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui ```

    ![Screenshot 2024-08-01 040955](https://github.com/user-attachments/assets/d241739f-d8b7-4a2f-9b6e-ee37e0dbb6ae)


    - #### Use command
   
      ``` sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher ```

      ![Screenshot 2024-08-01 060356](https://github.com/user-attachments/assets/b0e25ba0-6f7d-4aa0-a1d3-eea9812ed63b)


- #### Use command

  ``` catkin_make ```
  
![Screenshot 2024-08-01 054654](https://github.com/user-attachments/assets/75ae209b-7289-4ee1-be9b-7c7881b84c2a)



- ## launch and Control Motors

``` roslaunch robot_arm_pkg check_motors.launch ```

![Screenshot 2024-08-01 061109](https://github.com/user-attachments/assets/623f0e78-4cf2-4ed1-94cb-43069a42898e)


![Screenshot 2024-08-01 061217](https://github.com/user-attachments/assets/786db3b1-4440-452a-a62d-f7c1541532b1)

- ##  MoveIt Motion Planning Framework

 ``` roslaunch moveit_pkg demo.launch ``` 

 ![Screenshot 2024-08-01 061735](https://github.com/user-attachments/assets/829dc0dc-18df-41da-ac7f-cb94ff9b065c)


 
- ## Gazebo simulator
 ``` roslaunch robot_arm_pkg check_motors_gazebo.launch ```

 ![Screenshot 2024-08-01 061540](https://github.com/user-attachments/assets/6f5a7e96-b777-45e6-a7b6-dc9e77e45848)


![Screenshot 2024-08-01 061521](https://github.com/user-attachments/assets/cba4ec07-31c0-4200-bc28-11ea9c83b5ff)

