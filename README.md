# robotic-pick-and-place-

To run program: 

-> publish sample pointcloud on topic /cloud_pcd

In new terminal
1) cd pcd_files
2) rosrun pcl_ros pcd_to_pointcloud ck2_perpendicular.pcd 0.1


-> Run object recognition package

In new terminal
1) roscd object_detection
2) rosrun object_detection object_recognition 

The model file is in the object_recognition package in the folder /model_files


