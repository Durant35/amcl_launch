## amcl_launch
smart car amcl launch files on PC 

## How to use it
```shell
cd ~/catkin_ws/src
git clone 
cd ..
catkin_make amcl_launch
# you need to put the map built by Hector SLAM into src/amcl_launch/maps
roslaunch amcl_launch amcl_networking.launch map:=<build-map>.yaml
```
