cmake_minimum_required(VERSION 2.8.3)
project(acrobot_description)

## Find catkin macros and libraries
find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY urdf
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY rviz
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
