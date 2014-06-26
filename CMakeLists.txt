cmake_minimum_required(VERSION 2.8)
project( HoughCircles )
find_package( OpenCV REQUIRED )
add_executable( houghcircles houghcircles.cpp )
add_executable( HoughCircle_Demo HoughCircle_Demo.cpp )
target_link_libraries( houghcircles ${OpenCV_LIBS} )
target_link_libraries( HoughCircle_Demo ${OpenCV_LIBS} )

