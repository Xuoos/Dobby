# Dobby

Dobby is a lightweight, multi-platform, multi-architecture exploit hook framework.

- Minimal and modular library
- Multi-platform support(Windows/macOS/iOS/Android/Linux)
- Multiple architecture support(X86, X86-64, ARM, ARM64)

## CMake

Add this to CMakeLists.txt:

```
add_subdirectory(Dobby)
target_link_libraries(${CMAKE_PROJECT_NAME} dobby_static)
```

## Android.mk

Work in progress...

## Acknowledgments

[jmpews](https://github.com/jmpews)

[yujincheng08](https://github.com/yujincheng08)

[segfault-bilibili](https://github.com/segfault-bilibili)
