cmake_minimum_required(VERSION 2.8)
projcet(videoDetector)
find_package(OpenCV REQUIRED)
add_executable(videoDetector video.cpp)
target_link_libraries(videoDetector $ {OpenCV_LIBS})