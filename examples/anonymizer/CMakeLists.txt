add_executable(anonymizer anonymizer.cpp)

target_link_libraries(anonymizer elfio)
set_target_properties(anonymizer PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED YES
    CXX_EXTENSIONS NO
)
