# RoboND


## Packages

Navigation Stack
```
1. map_server
2. 
3. amcl
4. move_base: define a goal position for your robot in the map and the robot will navigate to that goal position.
It utilizes a costmap - where each part of the map is divided into which area is occupied, like walls or obstacles, and which area is unoccupied. As the robot moves around, a local costmap, in relation to the global costmap, keeps getting updated allowing the package to define a continuous path for the robot to move along.

```
