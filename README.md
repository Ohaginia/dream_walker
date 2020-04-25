<<<<<<< HEAD
# DreamWalker Project

***Develop a quadruped robot like Spot Mini***
![image3](https://user-images.githubusercontent.com/56295004/79933096-f68c5780-8489-11ea-8cdb-884ec8ff9c80.JPG "DreanWalker")

# DEMO
**gazebo**
![Screenshot from 2020-04-21 23-02-17](https://user-images.githubusercontent.com/56295004/79875861-33723300-8425-11ea-8e29-9f8bb4a9dade.png "gazebo")
=======
  # DreamWalker Project
***Develop a quadruped robot like Spot Mini***

# DEMO
**gazebo simulation**
![Screenshot from 2020-04-21 23-02-17](https://user-images.githubusercontent.com/56295004/79875861-33723300-8425-11ea-8e29-9f8bb4a9dade.png "gazebo simulation")
>>>>>>> origin/add-license-1

**Rviz**
![Screenshot from 2020-04-21 22-57-04](https://user-images.githubusercontent.com/56295004/79875887-3d943180-8425-11ea-8a85-ec60c3a5776a.png "Rviz")

# Features
<<<<<<< HEAD
This robot will be developed using a BLDC actuator optimized for a quadruped robot.  
Gait control is performed using general kinematics control, and stability is guaranteed by dynamics control.  
=======
This robot will be developed using a BLDC actuator optimized for a quadruped robot.    
Gait control is performed using general kinematics control, and stability is guaranteed by dynamics control.    
>>>>>>> origin/add-license-1
At this stage, the simulation environment is ready.  

# Environment

OS:Ubuntu 18.04.4 LTS  
<<<<<<< HEAD
CPU:Intel® Core™ i7-1065G7 CPU @ 1.30GHz × 8  
=======
CPU:Intel® Core™ i7-1065G7 CPU @ 1.30GHz × 8   
>>>>>>> origin/add-license-1
GPU:Intel® Iris(R) Plus Graphics (Ice Lake 8x8 GT2)  
ROS:Melodic  

# Usage

```bash
source ~/catkin_ws/devel/setup.bash
<<<<<<< HEAD
(source ~/catkin_ws/devel/setup.zsh)
cd ~/catkin_ws/src
git clone https://github.com/Ohaginia/dream_walker.git
cd ~/catkin_ws
catkin_make
roslaunch dream_walker gazebo.launch
roslaunch dream_walker display.launch model:=dream_walker.urdf 
=======
cd ~/catkin_ws/src
git clone https://github.com/Ohaginia/DreamWalker.git
cd ~/catkin_ws
catkin_make
roslaunch dream_walker gazebo.launch
roslaunch dream_walker display.launch model:=dw_descliption3.urdf 
>>>>>>> origin/add-license-1
```

# Note

<<<<<<< HEAD
**Change Fixed Frame of Global Options from map to dummy. (Default is map)**
![Screenshot from 2020-04-21 22-58-47](https://user-images.githubusercontent.com/56295004/79875866-35d48d00-8425-11ea-9159-f5843ac111af.png "note")　　

# Author

* Shoma Uehara  
* TRUST SMITH & COMPANY  
* Hamashoma@gmail.com  
=======
![Screenshot from 2020-04-21 22-58-47](https://user-images.githubusercontent.com/56295004/79875866-35d48d00-8425-11ea-9159-f5843ac111af.png)

Change Fixed Frame of Global Options from map to dummy.
(Default is map)


# Author

* Shoma Uehara
* TRUST SMITH & COMPANY
* Hamashoma@gmail.com
>>>>>>> origin/add-license-1

# License

"dream_walker" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
<<<<<<< HEAD
=======

>>>>>>> origin/add-license-1
