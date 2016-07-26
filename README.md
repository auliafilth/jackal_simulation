# jackal_simulation
This is an independent port of the code from Clearpath Robotics for simulating Jackal in ROS Jade.

# Install
To install you need to place this repo in your catkin workspace src. This repo uses submodules so you might need to pull them with this command in this repos root directory.  

``` git submodule update --init --recursive ```  

After that you need to resolve the deps needed to build. To do this run these commands in this repos root directory.

```
rosdep update
rosdep check --from-paths . --ignore-src --rosdistro your_distro
rosdep install --from-paths . --ignore-src --rosdistro your_distro -y
``` 
