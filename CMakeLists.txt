cmake_minimum_required(VERSION 3.14)

set(PROJECT_NAME cmake_project_example) # PROJECT_NAME이라는 변수를 선언함
set(CMAKE_CXX_STANDARD 17)

project(${PROJECT_NAME}) # ${}로 변수 사용함
add_executable(${PROJECT_NAME} src/main.cpp)

# cmake -Bbuild . -DCMAKE_BUILD_TYPE=Debug
# cmake --build build