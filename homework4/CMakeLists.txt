cmake_minimum_required(VERSION 3.10)
project(BezierCurve)

include_directories("D:/Code_Library/cpp/opencv-4.10.0/build/x64/mingw/install/include")
include_directories("D:/Code_Library/cpp/eigen-3.4.0")

find_package(OpenCV REQUIRED)

set(CMAKE_CXX_STANDARD 14)

add_executable(BezierCurve main.cpp)
target_link_libraries(BezierCurve "D:/Code_Library/cpp/opencv-4.10.0/build/x64/mingw/lib/libopencv_world460.dll.a")
# target_link_libraries(BezierCurve ${OpenCV_LIBRARIES})
