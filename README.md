# DreamWalker Project

***Develop a quadruped robot like Spot Mini***


# DEMO
**gazebo**
![Screenshot from 2020-04-21 23-02-17](https://user-images.githubusercontent.com/56295004/79875861-33723300-8425-11ea-8e29-9f8bb4a9dade.png "gazebo")

**Rviz**
![Screenshot from 2020-04-21 22-57-04](https://user-images.githubusercontent.com/56295004/79875887-3d943180-8425-11ea-8a85-ec60c3a5776a.png "Rviz")

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
![Screenshot from 2020-04-21 22-58-47](https://user-images.githubusercontent.com/56295004/79875866-35d48d00-8425-11ea-9159-f5843ac111af.png "note")
**Change Fixed Frame of Global Options from map to dummy. (Default is map)**

# Author

* Shoma Uehara  
* TRUST SMITH & COMPANY  
* Hamashoma@gmail.com  

# License

"dream_walker" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
