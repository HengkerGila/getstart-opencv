cmake_minimum_required(VERSION 3.5)

# project( DisplayImage )
project( MatMaskOperations )

find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )

# add_executable( DisplayImage src/DisplayImage.cpp )
add_executable( MatMaskOperations src/mat_mask_operations.cpp )

# target_link_libraries( DisplayImage ${OpenCV_LIBS} )
target_link_libraries( MatMaskOperations ${OpenCV_LIBS} )