  # DreamWalker Project
***Develop a quadruped robot like Spot Mini***

# DEMO
**gazebo simulation**
![Screenshot from 2020-04-21 23-02-17](https://user-images.githubusercontent.com/56295004/79875861-33723300-8425-11ea-8e29-9f8bb4a9dade.png "gazebo simulation")

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
cd ~/catkin_ws/src
git clone https://github.com/Ohaginia/DreamWalker.git
cd ~/catkin_ws
catkin_make
roslaunch
```

# Note

注意点などがあれば書く

# Author

作成情報を列挙する

* 作成者
* 所属
* E-mail

# License
ライセンスを明示する

"hoge" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

社内向けなら社外秘であることを明示してる

"hoge" is Confidential.
