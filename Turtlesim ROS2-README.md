# Manipulate with Turtlesim in ROS2

- ## First Run Turtlesim package in Ros2 humble

- Check environment variables by using this command:

  ``` printenv | grep -i ROS ```

  <img width="1440" alt="واحد" src="https://github.com/user-attachments/assets/085105eb-e412-488b-9206-e491e760922f">

- ## Now try installing the turtlesim package in ros2

``` sudo apt update ```
``` sudo apt install ros-humble-turtlesim ```

<img width="1440" alt="اثنين" src="https://github.com/user-attachments/assets/c50d249d-ff4a-44a4-8b99-540176336305">


- ## Check that the package is installed successfully

  ``` ros2 pkg executables turtlesim ```

  <img width="1440" alt="ثلاث" src="https://github.com/user-attachments/assets/b60c8115-d4c9-4776-a46e-1162aeb3e288">

- ## Run turtlesim node

  ``` ros2 run turtlesim turtlesim_node ```

  <img width="1440" alt="ارب" src="https://github.com/user-attachments/assets/f557f154-51e5-4028-9084-7e7787c5a790">


- ## Run turtle teleop node in a new terminal

  ``` ros2 run turtlesim turtle_teleop_key ```

  ![خمس](https://github.com/user-attachments/assets/682fa708-ebae-4e62-a751-2ff3c6bfaace)
