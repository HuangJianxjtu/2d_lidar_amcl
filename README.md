# AMCL for 2D LIDAR

ROS的AMCL源码

## 0.dependencies

[raybot_simu](https://github.com/HuangJianxjtu/raybot_gazebo), amcl

## 1.How to use

```bash
roslaunch mbot_gazebo view_mbot_with_laser_gazebo.launch
roslaunch mbot_teleop mbot_teleop.launch
rosrun map_server map_server map.yaml
rosrun amcl amcl
rviz
```
