<p align="center">
    <b>Welcome to my page! 👋</b><br><br>
    <i>
        My name is Jake McLaughlin.<br>
        I am completing my Masters Degree in Robotics part time at the Unversity of Waterloo, however I am part of the SRI Lab at UCLA.<br>
        My research interests are in tightly coupled SLAM and its applications to 3D reconstruction.<br>
    </i><br>
    <a href="https://www.linkedin.com/in/jakefmclaughlin">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
    </a>
    <a href="https://sri-lab.seas.ucla.edu/">
        <img src="https://img.shields.io/badge/SRILab-blue?style=flat-square&logo=SRILab" alt="SRILab">
    </a>
</p>

### Languages/Technologies
[![Python](https://img.shields.io/badge/python-black?style=for-the-badge&logo=python)](https://github.com/jakemclaughlin6)
[![C++](https://img.shields.io/badge/c++-black?style=for-the-badge&logo=cplusplus)](https://github.com/jakemclaughlin6)
[![ROS](https://img.shields.io/badge/ros-black?style=for-the-badge&logo=ros)](https://github.com/jakemclaughlin6)
[![ROS](https://img.shields.io/badge/opencv-black?style=for-the-badge&logo=opencv)](https://github.com/jakemclaughlin6)
[![ROS](https://img.shields.io/badge/pcl-black?style=for-the-badge&logo=pcl)](https://github.com/jakemclaughlin6)
[![ROS](https://img.shields.io/badge/eigen-black?style=for-the-badge&logo=eigen)](https://github.com/jakemclaughlin6)
[![Linux](https://img.shields.io/badge/linux-black?style=for-the-badge&logo=Linux)](https://github.com/jakemclaughlin6)

<p align="center">
  <a href="https://github.com/jakemclaughlin6">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jakemclaughlin6&theme=transparent" />
  </a>
  <a href="https://github.com/jakemclaughlin6">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=jakemclaughlin6&hide_border=true&card_width=338&theme=transparent" />
  </a>
  <a href="https://github.com/jakemclaughlin6">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=jakemclaughlin6&theme=transparent" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/jakemclaughlin6">
    <img src="https://komarev.com/ghpvc/?username=jakemclaughlin6&color=blue&style=flat)" />
  </a>
</p>

## Projects

### Visual Inertial Odometry

This video was taken of the Visual-Inertial-Odometry I implemented, as part of [beam_slam](https://github.com/BEAMRobotics/beam_slam), from the ground up using Locus's [fuse](https://github.com/locusrobotics/fuse) repository, along with an in lab library [libbeam](https://github.com/BEAMRobotics/libbeam), where many of my contributions lie. The goal of this VIO implementation was to provide a platform for further research and enhancement (learning based feature tracking, MLPnP, semantic segmentation etc). It was also implemented with the coupling of LiDAR odometry in mind, along with coupled Visual-LiDAR place recognition for robust and accurate loop closures.

https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/5c63e5da-b821-4174-8d1e-e45739183d65

---

### Visual-Lidar Map Alignment

As part of my thesis work, I have implemented an offline tool to automatically align maps generated from SLAM. This approach to alignment allows for more robust, decoupled approached to visual or lidar place recognition as there is no real-time constraint. The purpose of this work is to allow for repeated inspections of the same area, without the need to be confined to one of the few multi-session SLAM packages (namely ORB-SLAM3, RTAB-map, maplab and lt-mapper). See my repository [vl_traj_alignment](https://github.com/jakemclaughlin6/vl_traj_alignment) for implementation.

Before Alignment            |  After Alignment
:-------------------------:|:-------------------------:
![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/62acc213-0652-4563-bd99-86005a45f677)  |  ![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/15605e65-9d25-4fbe-8231-6c78022ba7fa)
![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/90e93842-c322-4f4a-9234-8d082e8ae903)  |  ![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/9c9f7094-b612-4cad-95af-7d52fcd630a6)

