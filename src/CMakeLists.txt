set(MAIN_TARGET ${PROJECT_NAME})

add_executable(${MAIN_TARGET})

target_sources(${MAIN_TARGET} PRIVATE main.cpp)

set_target_properties(${MAIN_TARGET}
                      PROPERTIES CXX_STANDARD
                                 17
                                 CXX_STANDARD_REQUIRED
                                 true)
