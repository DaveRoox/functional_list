include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runTest basic_check.cpp)

target_link_libraries(runTest gtest gtest_main)
target_link_libraries(runTest ${functional})