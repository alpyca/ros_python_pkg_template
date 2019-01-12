cmake_minimum_required(VERSION 2.8.3)
project({{cookiecutter.project_slug}})
find_package(catkin REQUIRED COMPONENTS
  rospy
  message_generation 
  std_msgs)
catkin_python_setup()

catkin_install_python(PROGRAMS
    src/{{cookiecutter.project_slug}}/__init__.py
DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}/{{cookiecutter.project_slug}})

generate_messages(DEPENDENCIES std_msgs)

