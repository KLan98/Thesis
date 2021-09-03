robot_localization
==================

robot_localization is a package of nonlinear state estimation nodes. The package was developed by Charles River Analytics, Inc.

Please see documentation here: http://docs.ros.org/melodic/api/robot_localization/html/index.html

For this project I use the Extended Kalman Filter configuration file to publish /ekf_map_to_odom and /ekf_odom_to_basefootprint nodes. The configuration file can be found in robot_localization_ekf/params/ekf_map.yaml and robot_localization_ekf/params/ekf_odom.yaml directories. User can just copy these file and paste them to the robot_localization package.
