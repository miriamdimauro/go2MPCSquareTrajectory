# README

## Overview
This project is a fork of the original Unitree Go2 code combined with modifications based on the repository [unitreeMPC_guide](https://github.com/Mr-Y-B-L/unitreeMPC_guide/tree/master/src/unitreeMPC_guide/unitreeMPC_guide/src). The goal is to implement and refine a Model Predictive Control (MPC) algorithm for the Go2 robot, focusing on locomotion tasks such as trotting along a squared trajectory, both with and without rotation.

## Project Background
The MPC implementation for the Go1 robot from the repository [unitreeMPC_guide](https://github.com/Mr-Y-B-L/unitreeMPC_guide/tree/master/src/unitreeMPC_guide/unitreeMPC_guide/src) was adapted for the Go2 robot. The original code has been modified to accommodate the specific requirements and configurations of the Go2 robot, maintaining the core functionality of the Model Predictive Control algorithm.

## Features
- Square trajectory tracking without rotation
- Square trajectory tracking with 90° rotations at each vertex
- Velocity control proportional to positional error
- Yaw control to maintain orientation toward the next vertex

## Build
Please refer to Unitree official configuration [https://github.com/unitreerobotics/unitree_guide] and to the repository [unitreeMPC_guide](https://github.com/Mr-Y-B-L/unitreeMPC_guide) for detailed instructions on dependencies and configuration.

## License
This project is released under the same license as the original Unitree SDK and unitreeMPC_guide. Please refer to the respective licenses in the original repositories.

## Acknowledgments
- [Unitree Robotics](https://github.com/unitreerobotics/unitree_guide)
- [unitreeMPC_guide by Mr-Y-B-L](https://github.com/Mr-Y-B-L/unitreeMPC_guide)
  
## Authors
- Cinardi Nicoletta
- Di Mauro Miriam
- Finocchiaro Carla
- Panebianco Gaia

For further information contact the project maintainers.

