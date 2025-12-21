#  LiDAR SLAM & Loop Closure Optimization

![C++](https://img.shields.io/badge/Language-C%2B%2B17-blue)
![ROS2](https://img.shields.io/badge/Framework-ROS2%20Humble-green)
![Status](https://img.shields.io/badge/Status-Research%20Phase-yellow)

##  Project Overview
Simultaneous Localization and Mapping (SLAM) is the backbone of autonomous mobile mapping. This project aims to implement a **LiDAR-based SLAM system** focusing on reducing drift in large-scale environments through optimized **Loop Closure Detection**.

## Objectives
- **Preprocessing:** Downsampling raw point clouds using Voxel Grids.
- **Odometry:** Implement Scan-to-Map matching (ICP/NDT algorithms).
- **Optimization:** Backend graph optimization (g2o or GTSAM) to correct trajectory drift.
- **Loop Closure:** Geometric verification to prevent false positives in repetitive environments.

## Tech Stack
- **Core:** C++, Python
- **Middleware:** ROS 2 (Robot Operating System)
- **Libraries:** PCL (Point Cloud Library), GTSAM
- **Data:** KITTI Odometry Benchmark / Custom Rosbags

## Roadmap
- [ ] Configure ROS 2 workspace and dependencies.
- [ ] Implement basic ICP odometry node.
- [ ] Integrate backend Pose Graph Optimization.
- [ ] Benchmark against standard datasets.

---
Melih Levent Aslan | M.Sc. Student, University of Bonn
