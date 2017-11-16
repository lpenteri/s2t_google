cmake_minimum_required(VERSION 2.8.3)
project(s2t_google)

find_package(catkin REQUIRED)

###################################
## catkin specific configuration ##
###################################
catkin_package()

#############
## Install ##
#############

install(PROGRAMS
   streamit.js
   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
