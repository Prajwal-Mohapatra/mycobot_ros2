# mycobot_ros2

A personal practice repository for learning and experimenting with **ROS2** and **Gazebo**.

## Purpose

This repo is not intended for production use. It exists solely to:

- Build hands-on familiarity with ROS2 concepts (nodes, topics, services, actions, etc.)
- Explore robot simulation using Gazebo
- Experiment with URDF/Xacro robot descriptions
- Practice ROS2 package structure and tooling (colcon, rviz2, etc.)

## Robot

The practice robot used here is the **myCobot** a small, 6-DOF collaborative robot arm by Elephant Robotics.

## Credits

Inspired by and based on the excellent work of **Automatic Addison**:

- 🔗 [automaticaddison/mycobot_ros2](https://github.com/automaticaddison/mycobot_ros2)

All credit for the original implementation, tutorials, and design goes to them. This repository is purely a personal learning exercise built on top of their foundation.

## Requirements

- ROS2 (Jazzy)
- Gazebo
- `colcon` build tool

## Getting Started

```bash
cd ros2_ws/src

# Clone the repo
git clone https://github.com/Prajwal-Mohapatra/mycobot_ros2.git
cd mycobot_ros2

# Build
colcon build

# Source the workspace
source install/setup.bash
```

## License

For learning purposes only. Refer to the [original repository](https://github.com/automaticaddison/mycobot_ros2) for licensing information.
