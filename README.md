**BUCK- AUTONOMOUS MOBILE ROBOT FOR DEPTH-CAM AND 2D LIDAR MAPPING ,NAVIGATION**

OS: UBUNTU 22.04

ROS DISTRO: HUMBLE

Humble installation link::https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html


            
Packages needed:
        
        sudo apt install ros-humble-xacro
        sudo apt install python3-colcon-common-extensions
        sudo apt install ros-humble-joint-state-publisher-gui
        sudo apt install ros-humble-gazebo-ros-pkgs
        sudo apt install ros-humble-rtabmap-*

Clone this repo in your ros2 work directory using,

            git clone https://github.com/FERBIN12/Buck_ws.git
Then build the package in your workspace ,

            colcon build --symlink-install

ROBOT with 2 depth camera LAUNCHING COMMAND:

In terminal 

    ros2 launch model_py launch_sim.launch.py                        

Output:

![Screenshot from 2024-03-06 00-26-26](https://github.com/FERBIN12/Buck_ws/assets/126778624/1939c9e0-03e7-4af8-9f30-15ef3a2a3bae)
