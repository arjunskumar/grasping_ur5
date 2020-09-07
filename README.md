# grasping_ur5 

This ros package is a pick and place application using Universal Robot (UR5) and a RGBD/ Stereo Camera.

 [gpd](https://github.com/atenpas/gpd.git) was modified to detect the centroid of point cloud clusters.



### How to use this package?

```
roslaunch grasping_ur5 execute.launch
```

Subscribers: /detect_grasps/clustered_grasps 

Publishers : /object_pose

### Pick and Place with UR5 and Zed Stereo Camera


## Expected Output:
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/DSQBZ3Fy7N0/0.jpg)](https://www.youtube.com/watch?v=DSQBZ3Fy7N0)
