# Level Plane SLAM: Out-of-plane Motion Compensation in a Globally Stabilized Coordinate Frame for 2D SLAM

## Description
Welcome to the **Level Plane SLAM: Out-of-plane Motion Compensation in a Globally Stabilized Coordinate Frame for 2D SLAM** repository! This repository occompanies IEEE conference paper of the same name found here https://doi.org/10.1109/SMC53992.2023.10394614. The project was implimented in ROS Melodic Morenia and run on Ubuntu 18.04 (Bionic). Both platforms have since reached their end-of-life. As such work has been halted on adapting this project for these platforms.

## Status
**Halted**

The code in this repository is not yet finalized. In the future the code may be upgraded to work with the newest distrobution of ROS 2. Please check back later for updates. We appreciate your patience and understanding.

## Updates
We will post updates here. Stay tuned for the latest information.

**Level-Plane-SLAM Pseudocode**
For those interested in implimenting Level-Plane-SLAM here is the algorithm's high level pseudocode. Repeat these steps for each new LIDAR scan so that they can be used for 2D-LIDAR SLAM.

> Get LIDAR scan
> Get IMU measurement
> Convert IMU measurement into platform orientation
> Transform LIDAR scan into 3D using platform orientation
> Project into 2D

## Citation
S. Lovett, T. Paquette, B. DeBoon, S. Rajan and C. Rossa, "Level Plane SLAM: Out-of-Plane Motion Compensation in a Globally Stabilized Coordinate Frame for 2D SLAM," _2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC)_, Honolulu, Oahu, HI, USA, 2023, pp. 3355-3360, doi: 10.1109/SMC53992.2023.10394614. keywords: {Simultaneous localization and mapping;Three-dimensional displays;Laser radar;Tracking;Navigation;Two-dimensional displays;Adaptive filters;SLAM;scan matching;signal filtering;LIDAR odometry;Lidar-IMU fusion;Hector SLAM},




