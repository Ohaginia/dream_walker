# DreamWalker Project

***Develop a quadruped robot like Spot Mini***


# DEMO

"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる

# Features
This robot will be developed using a BLDC actuator optimized for a quadruped robot.  
Gait control is performed using general kinematics control, and stability is guaranteed by dynamics control.  
At this stage, the simulation environment is ready.  

# Environment

OS:Ubuntu 18.04.4 LTS  
CPU:Intel® Core™ i7-1065G7 CPU @ 1.30GHz × 8  
GPU:Intel® Iris(R) Plus Graphics (Ice Lake 8x8 GT2)  
ROS:Melodic  

# Usage

DEMOの実行方法など、"hoge"の基本的な使い方を説明する

```bash
source ~/catkin_ws/devel/setup.bash
(source ~/catkin_ws/devel/setup.zsh)
cd ~/catkin_ws/src
git clone https://github.com/Ohaginia/dream_walker.git
cd ~/catkin_ws
catkin_make
roslaunch dream_walker gazebo.launch
roslaunch dream_walker display.launch model:=dream_walker.urdf 
```

# Note

**Change Fixed Frame of Global Options from map to dummy. (Default is map)**

# Author

*Shoma Uehara
*TRUST SMITH & COMPANY
*Hamashoma@gmail.com

# License

"dream_walker" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
