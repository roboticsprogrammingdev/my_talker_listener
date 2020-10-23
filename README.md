# my_talker_listener
This is a ROS package to demonstrate that two nodes, which are implemented in different languages, communicate with each other via messages.

## Installation
1. Create a catkin workspace.
```bash
~$ mkdir -p catkin_ws/src
~$ cd catkin_ws/src
~/catkin_ws/src$ catkin_init_workspace
```

2. Clone the repository.
```bash
~/catkin_ws/src$ git clone https://github.com/roboticsprogammingdev/my_talker_listener.git
~/catkin_ws/src$ cd ..
```

3. Build the source and install the executables.
```bash
~/catkin_ws$ catkin_make
~/catkin_ws$ catkin_make install
```

## Demonstration
Launch the `.launch` file.
```bash
~/catkin_ws$ roslaunch my_talker_listener talker_listener.launch
```

## Blog post
Read [Creating a ROS package](https://blog.roboticsprogamming.dev/2020/10/my-talker-listener.html).
