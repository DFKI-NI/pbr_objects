cmake_minimum_required(VERSION 3.8)
project(pbr_objects)

find_package(ament_cmake REQUIRED)


#############
## Install ##
#############

## Mark other files for installation (e.g. launch and bag files, etc.)
install(DIRECTORY
  config
  meshes
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
