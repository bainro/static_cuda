cmake_minimum_required(VERSION 3.21)
project(CudaTemplate LANGUAGES CUDA CXX)

enable_language(CUDA)
find_package(CUDAToolkit)

ADD_SUBDIRECTORY(SomeCudaLib)
ADD_SUBDIRECTORY(MainProject)
