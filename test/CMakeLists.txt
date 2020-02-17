set(BINARY ${CMAKE_PROJECT_NAME}_test)

add_executable(${BINARY} Formula-test.cpp)
target_link_libraries(${BINARY} gtest_main ${CMAKE_PROJECT_NAME}_lib)
add_test(NAME ${BINARY} COMMAND ${BINARY})
