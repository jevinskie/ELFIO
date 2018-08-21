add_executable(write_obj write_obj.cpp)

target_link_libraries(write_obj elfio)
set_target_properties(write_obj PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)
