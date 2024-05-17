cmake_minimum_required(VERSION 3.1...3.15)

project(NetChat VERSION 1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(MY_APP_SOURCES main.cpp)

add_executable(NetChat ${MY_APP_SOURCES})

# Add your include directories if different than default
# target_include_directories(MyApp PRIVATE /path/to/your/includes)

# If you have any libraries that need linking, do it here
# target_link_libraries(MyApp PRIVATE /path/to/your/library)