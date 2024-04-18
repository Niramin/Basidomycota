# CMakeList.txt : CMake project for Basidomycota, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Basidomycota "Basidomycota.cpp" "Basidomycota.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Basidomycota PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
