### Hi there 👋
I'm Jake and I am an Autonomy Developer with OTTO Motors!

I did my Masters at the University of Waterloo focusing on tightly coupled Visual-Lidar SLAM for automated infrastructure inspections.

I'm currently working at OTTO Motors as a part of the Perception team working on robust SLAM in warehouse environments, my specialty is within calibration of the various sensors on our AMR platforms.

##
<p align="center">
    <a href="https://www.linkedin.com/in/jakefmclaughlin">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
    </a>
    <a href="https://ottomotors.com/">
        <img src="https://img.shields.io/badge/OTTO-purple?style=flat-square&logo=OTTO" alt="OTTO">
    </a>
</p>

<p align="center">
  <a href="https://github.com/jakemclaughlin6">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jakemclaughlin6&theme=github" />
  </a>
  <a href="https://github.com/jakemclaughlin6">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=jakemclaughlin6&hide_border=true&card_width=338&theme=github-light" />
  </a>
</p>
<p align="center">
    <a href="https://github.com/Fixit-Davide/github-readme-stats">
      <img height=150 align="center" src="https://github-readme-stats-sigma-five.vercel.app/api?username=jakemclaughlin6&show_icons=true&theme=github-light&rank_icon=github&count_private=true" />
    </a>
    <a href="https://github.com/anuraghazra/convoychat">
      <img height=150 align="center" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs?username=jakemclaughlin6&layout=compact&langs_count=8&card_width=310&theme=github-light" />
    </a>
</p>

## Projects

<details>
<summary><b><u><font size="+1">Visual Inertial Odometry</font></u></b></summary>

This video was taken of the Visual-Inertial-Odometry I implemented, as part of [beam_slam](https://github.com/BEAMRobotics/beam_slam), from the ground up using Locus's [fuse](https://github.com/locusrobotics/fuse) repository, along with an in lab library [libbeam](https://github.com/BEAMRobotics/libbeam), where many of my contributions lie. The goal of this VIO implementation was to provide a platform for further research and enhancement (learning based feature tracking, MLPnP, semantic segmentation etc). It was also implemented with the coupling of LiDAR odometry in mind, along with coupled Visual-LiDAR place recognition for robust and accurate loop closures.

https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/5c63e5da-b821-4174-8d1e-e45739183d65

</details>

<details>
<summary><b><u><font size="+1">Visual-Lidar Map Alignment</font></u></b></summary>

As part of my thesis work, I have implemented an offline tool to automatically align maps generated from SLAM. This approach to alignment allows for more robust, decoupled approached to visual or lidar place recognition as there is no real-time constraint. The purpose of this work is to allow for repeated inspections of the same area, without the need to be confined to one of the few multi-session SLAM packages (namely ORB-SLAM3, RTAB-map, maplab and lt-mapper). See my repository [vl_traj_alignment](https://github.com/jakemclaughlin6/vl_traj_alignment) for implementation.

Before Alignment            |  After Alignment
:-------------------------:|:-------------------------:
![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/62acc213-0652-4563-bd99-86005a45f677)  |  ![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/15605e65-9d25-4fbe-8231-6c78022ba7fa)
![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/90e93842-c322-4f4a-9234-8d082e8ae903)  |  ![](https://github.com/jakemclaughlin6/jakemclaughlin6/assets/25440002/9c9f7094-b612-4cad-95af-7d52fcd630a6)

</details>

