cmake_minimum_required(VERSION 3.12)
project(Advanced2)

set(CMAKE_CXX_STANDARD 11)

add_executable(Advanced2 main.cpp cmake-build-debug/interface.h cmake-build-debug/MyEmployee.cpp cmake-build-debug/MyPlane.cpp cmake-build-debug/MyFlight.cpp cmake-build-debug/MyCustomer.cpp cmake-build-debug/myReservation.cpp cmake-build-debug/DataBase.cpp cmake-build-debug/DataBase.h cmake-build-debug/MyCustomer.h cmake-build-debug/MyFlight.h cmake-build-debug/MyEmployee.h cmake-build-debug/Date.cpp cmake-build-debug/MyPlane.h cmake-build-debug/MyReservation.h cmake-build-debug/MyImplementation.cpp cmake-build-debug/MyImplementation.h)