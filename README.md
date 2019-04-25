# RoboND-MapMyWorld
#SLAM #ROS

In this project, Graph-SLAM which is an efficient algorithm for simultaneous mapping and localization problems is implemented and tested.
Robot model used in this project is built upon previous model that was used in RoboND-Localization project, Briefly, it consists of simple base with 2 differential wheels and 2 caster wheels to balance it in addition to RGB camera and Laser range sensor.
Testing process is performed in gazebo simulated environment which provides access to variety of models and worlds which gives us the advantage to observe the efficiency in different fields.
Through this process, input data is provided through RGBD camera and Laser Range Finder sensor to specific ROS package which is responsible for performing mapping and localization calculations and giving the results.
Final result consists of 2D and 3D maps of the environment and database of the completed process.
