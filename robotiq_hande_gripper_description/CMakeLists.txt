cmake_minimum_required(VERSION 2.8.3)
project(robotiq_hande_gripper_description)

find_package(catkin REQUIRED)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES ur_e_description
#  CATKIN_DEPENDS urdf
#  DEPENDS system_lib
)


install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
