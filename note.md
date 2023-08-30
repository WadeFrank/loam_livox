# 代码框架
roslaunch会启动两个程序，source/laser_feature_extractor.cpp和source/laser_mapping.cpp


## laser_feature_extractor.hpp
Laser_feature类
* 构造函数Laser_feature()
  * init_ros_env()
    * laserCloudHandler()
      * extract_laser_features()
          * compute_features()
          * projection_scan_3d_2d()