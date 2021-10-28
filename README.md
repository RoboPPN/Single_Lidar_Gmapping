# 使用单个激光雷达建图
使用ydlidar G4雷达完成gmapping建图

1. 需要一个提供`odom`的功能包`laser_scan_matcher`
2. 需要安装一个ROS包
```shell
sudo apt install ros-melodic-csm
```

将代码克隆下来
```shell
https://github.com/RoboPPN/Single_Lidar_Gmapping.git
```
在工作空间编译通过，接上ydlidar G4雷达在终端运行：
```shell
roslaunch laser_scan_matcher demo_gmapping.launch
```
就可以跑了

主要在`demo_gmapping.launch`文件做修改




