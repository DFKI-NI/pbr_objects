cmake_minimum_required(VERSION 3.5.1)
project(pbr_objects)

find_package(catkin REQUIRED)

catkin_package()

#############
## Install ##
#############

## Mark other files for installation (e.g. launch and bag files, etc.)
install(DIRECTORY
  config
  meshes
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
