# LSD-SLAM: Large-Scale Direct Monocular SLAM

LSD-SLAM is a novel approach to real-time monocular SLAM. It is fully direct (i.e. does not use keypoints / features) and creates large-scale, 
semi-dense maps in real-time on a laptop. For more information see
[http://vision.in.tum.de/lsdslam](http://vision.in.tum.de/lsdslam)
where you can also find the corresponding publications and Youtube videos, as well as some 
example-input datasets, and the generated output as rosbag or .ply point cloud.


### Related Papers

* **LSD-SLAM: Large-Scale Direct Monocular SLAM**, *J. Engel, T. Schöps, D. Cremers*, ECCV '14

* **Semi-Dense Visual Odometry for a Monocular Camera**, *J. Engel, J. Sturm, D. Cremers*, ICCV '13

## NOTE
I tried to follow the instructions provided by the [original LSD SLAM repository](https://github.com/tum-vision/lsd_slam) but faced a few errors while creating the ros pakcage. I followed several suggestions and tracked all the issues and was finally able to get it working. 
Links to some of the issues that helped me are listed as follows: 

- https://github.com/tum-vision/lsd_slam/issues/238
- https://github.com/tum-vision/lsd_slam/issues/301
- https://github.com/kevin-george/lsd_slam/issues/1

The `src` folder contains the ROS package for LSD SLAM that works well for me. I am using **Ubuntu 16.04.6** and **ROS Kinetic**.
