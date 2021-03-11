# rosidl-ws
This repo is a temporary one to send my code to reproduce [this issue](https://github.com/ros2/examples/issues/303).

## Instructions for Use
Clone this repo, then
```bash
cd rosidl_ws
source /opt/ros/foxy/setup.bash
colcon build
```
Then in a separate terminal
```bash
cd rosidl_ws
source /opt/ros/foxy/setup.bash
. install/setup.bash
```
Any of these commands, which run the tutorial scripts edited for custom interfaces, return the `rosidl` error.
```bash
ros2 run py_pubsub talkercustom 
ros2 run py_pubsub listenercustom 
ros2 run py_srvcli servicecustom
ros2 run py_srvcli clientcustom
```