add_executable(writer writer.cpp)

target_link_libraries(writer elfio)
set_target_properties(writer PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)
