cmake_minimum_required(VERSION 3.10)

project(objDet)

set(OpenCV_DIR D:/cpp/YouTube/opencv/build)
find_package(OpenCV REQUIRED)

add_executable(${PROJECT_NAME} src/Main.cpp)
target_link_libraries(${PROJECT_NAME} ${OpenCV_LIBS})
