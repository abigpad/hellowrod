cmake_minimum_required(VERSION 4.1)

project("helloword" 
  VERSION 1.0.0
  LANGUAGES C
)


set(src
    main.c
)
include_directories(${CMAKE_SOURCE_DIR})

add_executable(main ${src})


