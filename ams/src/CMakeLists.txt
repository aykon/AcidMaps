CMAKE_MINIMUM_REQUIRED (VERSION 2.8) 
PROJECT (ACID_MAPS_LIB) 

FILE(GLOB_RECURSE sources *.cc)
ADD_LIBRARY (acid-maps SHARED ${sources})

SET(CMAKE_BUILD_TYPE Release)

