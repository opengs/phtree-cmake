## PH-Tree cmake friendly library

Copy of library https://github.com/improbable-eng/phtree-cpp with friendy cmake

### Usage
#### Install
```
    mkdir build
    cd build
    cmake ..
    cmake --install .
```

#### Usage
```
    project("example")

    find_package(phtree CONFIG REQUIRED)

    add_executable(${PROJECT_NAME} src/main.cc)
    target_link_libraries(${PROJECT_NAME} phtree::phtree)
```