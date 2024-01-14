cmake_minimum_required(VERSION 3.6)

project("raytracing")

add_executable("raytracing" 
    src/main.cpp 
    src/vec3.hpp 
    src/color.hpp 
    src/ray.hpp
    src/hittable.hpp
    src/hittable_list.hpp
    src/camera.hpp
    src/rt.hpp
    src/sphere.hpp
)
