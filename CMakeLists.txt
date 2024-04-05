cmake_minimum_required(VERSION 3.5)
project(smart_template_description)

find_package(ament_cmake REQUIRED)

include_directories(
)


install(
  DIRECTORY launch urdf meshes
  DESTINATION share/${PROJECT_NAME}
)


#############
## Testing ##
#############

## Add gtest based cpp test target and link libraries
# catkin_add_gtest(${PROJECT_NAME}-test test/test_fusion2urdf.cpp)
# if(TARGET ${PROJECT_NAME}-test)
#   target_link_libraries(${PROJECT_NAME}-test ${PROJECT_NAME})
# endif()

## Add folders to be run by python nosetests
# catkin_add_nosetests(test)
