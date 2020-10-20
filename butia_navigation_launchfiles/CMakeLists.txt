cmake_minimum_required(VERSION 2.8.3)
project(butia_navigation_launchfiles)

catkin_package()

#install(DIRECTORY 
#   launch 
#   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )

install(PROGRAMS
  nodes/enable_motors_r.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
