# OpenCV-CPP

* Create a project folder
* Press Ctrl+shift+P to open the Command Palette
* Select the CMake: Configure
* Select the x86 version
* Enter the project name, then CMakeLists.txt will be generated and main.cpp file will be created
* Add these lines to the CMakeLists.txt
    * find_package( OpenCV REQUIRED )
    * include_directories( \${OpenCV_INCLUDE_DIRS})
    * target_link_libraries( \${PROJECT_NAME} \${OpenCV_LIBS})
* When the cmake file is saved, the build happens
* Edit the main.cpp code and run it.

