# jackal_simulation
This is an independet port of the code from Clearpath Robotics for simulation Jackal in ROS Jade and Kinetic

# Install
To install you need to place this repo in your catkin workspace src. After that you need to resolve the deps needed for these to build. To do this go into the gazebo_ros_pkgs director and enter this command.

```
rosdep update
rosdep check --from-paths . --ignore-src --rosdistro your_distro
rosdep install --from-paths . --ignore-src --rosdistro your_distro -y
``` 
