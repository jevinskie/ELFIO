add_executable(elfdump elfdump.cpp)

target_link_libraries(elfdump elfio)
set_target_properties(elfdump PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)
