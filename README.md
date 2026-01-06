# Development Instructions
Path of newly added cpp file should be inserted in the cmake file.
```cmake
add_executable(nn_scratch 
    src/main.cpp
    src/new-folder/new-cpp.cpp
)
```
Then run, `cmake -S . -B build -DCMAKE_EXPORT_COMPILE_COMMANDS=1` for clangd to work.
