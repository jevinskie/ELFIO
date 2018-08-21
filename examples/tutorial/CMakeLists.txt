add_executable(tutorial tutorial.cpp)

target_link_libraries(tutorial elfio)
set_target_properties(tutorial PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)
