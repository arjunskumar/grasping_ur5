# Grasping_UR5

This package is a pick and place application using Universal Robot (UR5) and a RGBD/ Stereo Camera.

 [gpd] (https://github.com/atenpas/gpd.git) was modified to detect the centroid of point cloud clusters.



### How to use this package?

```
roslaunch grasping_ur5 execute.launch
```

Subscribers: /detect_grasps/clustered_grasps 

Publishers : /object_pose