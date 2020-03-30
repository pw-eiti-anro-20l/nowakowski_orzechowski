cmake_minimum_required(VERSION 2.8.3)
project(lab01)
find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
)
catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES lab1
#  CATKIN_DEPENDS rospy
#  DEPENDS system_lib
)
include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
