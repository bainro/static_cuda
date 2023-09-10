cmake_minimum_required(VERSION 2.8)

ADD_EXECUTABLE(main src/main.cpp)
TARGET_LINK_LIBRARIES(main simplecuda)
message(CUDA_rt_LIBRARY="${CUDA_rt_LIBRARY}")
