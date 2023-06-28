# asio_restaurant

Simple demonstration of asynchronous execution using timers and strand with Boost.Asio

## Build

```shell
mkdir build && cd build
conan install .. -of .
cmake --preset conan-release ..
cmake --build .
```
