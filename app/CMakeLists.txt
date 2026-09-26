cmake_minimum_required(VERSION 3.20.0)

find_package(Zephyr REQUIRED)
project(my_zephyr_app) #Has to be called after find_package(Zephyr REQUIRED)  

target_sources(app PRIVATE src/main.cpp)    #the target is called app
