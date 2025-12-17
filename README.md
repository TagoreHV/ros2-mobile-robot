# ROS 2 Mobile Robot Simulation

A ROS 2 Humble based edge detection mobile robot simulation workspace.

## Packages
- bot_bringup
- bot_controller
- bot_description
- bot_script

## Build & Run
```bash
colcon build
source install/setup.bash
ros2 launch bot_bringup simulated_robot.launch.py
ros2 run bot_script edge_detection 
