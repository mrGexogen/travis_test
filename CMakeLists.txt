project(travis_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(
        SOURCE_FILES
        main.cpp
)

add_executable(travis_test ${SOURCE_FILES})