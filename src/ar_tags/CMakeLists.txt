cmake_minimum_required(VERSION 2.8.3)
project(ar_tags)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
  geometry_msgs
)

catkin_python_setup()

catkin_package()

include_directories(${catkin_INCLUDE_DIRS})
