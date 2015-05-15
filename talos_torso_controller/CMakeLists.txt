cmake_minimum_required(VERSION 2.8.3)
project(talos_torso_controller)

find_package(catkin REQUIRED)

catkin_package(
)

install(DIRECTORY extra DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
