# ESP-IDF-CPP-Template
**Quick Application Firmware Template to get your started**

## How to use
 > Clone `git clone https://github.com/sukesh-ak/ESP-IDF-CPP-Template.git`  
 > Set device target `idf.py set-target esp32` or esp32s2 / esp32c3 / esp32s3  
 > Change firmware/project name in CMakeLists.txt file in the root  
 > Run `idf.py menuconfig`  
 > Build `idf.py build`  
 > Flash `idf.py -p <com-port> flash`  

## Example folder contents

The project **sample_project** contains one source file in C++ language [main.cpp](main/main.cpp). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt
├── main
│   ├── CMakeLists.txt
│   └── main.cpp
└── README.md                  This is the file you are currently reading
```

