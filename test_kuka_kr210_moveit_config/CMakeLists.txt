cmake_minimum_required(VERSION 2.8.3)
project(test_kuka_kr210_moveit_config)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
