# Build
## Requirements
* C++ compiler

| Compiler | Version |
|----------|---------|
| GCC      | 5+      |
| Clang    | 3.6+    |
| MSVC     | 19.10+  |
* Cmake 3.8+
* LLVM 5
* Catch2s

## Build
### macOS
```
brew install llvm cmake git catch2
git clone https://github.com/lzmru/north
cd north
cmake . -DCMAKE_BUILD_TYPE=RELEASE
make
```