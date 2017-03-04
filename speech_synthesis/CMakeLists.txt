cmake_minimum_required(VERSION 2.8.3)
project(speech_synthesis)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  rospy
  speech_synthesis_msgs
  speech_synthesis_srvs
  std_msgs
)


catkin_package(
 # INCLUDE_DIRS include
#  LIBRARIES speech_synthesis
  CATKIN_DEPENDS  rospy speech_synthesis_msgs speech_synthesis_srvs std_msgs
#  DEPENDS system_lib
)

