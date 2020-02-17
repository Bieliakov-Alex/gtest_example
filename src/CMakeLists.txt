set(BINARY ${CMAKE_PROJECT_NAME})

add_executable(${BINARY}_run main.cpp
                             Formula.cpp
)

add_library(${BINARY}_lib STATIC main.cpp
                                 Formula.cpp
)
