cmake_minimum_required(VERSION 3.15)
project(butterfly_app)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES  butterfly_app.cc
        butterfly_app.hh
        ofp_builder.cc
        ofp_builder.hh
        )

include_directories(src/include
        src/nox)

add_executable(butterfly_app ${SOURCE_FILES})
