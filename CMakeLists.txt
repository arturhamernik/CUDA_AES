cmake_minimum_required(VERSION 3.28)
project(CUDA_AES2 CUDA)

set(CMAKE_CUDA_STANDARD 17)

add_executable(CUDA_AES2 main.cu)

set_target_properties(CUDA_AES2 PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
