cmake_minimum_required(VERSION 2.8.3)
project(gazebo_world_library)

find_package(catkin REQUIRED COMPONENTS
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES crab_gazebo
#  CATKIN_DEPENDS gazebo_plugins gazebo_ros roscpp rospy
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
