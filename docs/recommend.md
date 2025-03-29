# 参考资料与项目推荐

## 资源推荐

- hackingcpp.com
- learncpp.com
- cppreference.com
- godbolt.org
- cppinsights.io
- quick-bench.com
- github.com
- stackoverflow.com
- effective c++
- 小彭老师 (双笙子佯谬)
- 白律师 (mq白cpp)

## 项目推荐

### 集大成者

- boost
- qt
- llvm

### 现代

- fmt
- spdlog
- nlohmann-json
- ranges-v3
- matchit.cpp
- utfcpp

### 实用扩展

- absl
- tsl-robin-map
- backward-cpp
- iguana
- magic_enum
- structopt

### 高性能

- tbb
- cub
- cutlass
- thrust
- highway
- amgcl
- eigen
- numcpp

### 图形学

- sfml
- libigl
- openvdb
- cgal

### 古代

- opencv
- nothings/stb
- google/benchmark
- rapidjson
- jsoncpp
- gtest
- catch3
- tinyxml2
- poco
- incbin

### 小彭老师课程

- parallel101/course
- parallel101/opengltutor
- parallel101/openglslides
- parallel101/cppguidebook
- parallel101/simdtutor

### 小彭老师自研

- zenustech/zeno
- archibate/co_async
- parallel101/stl1weekend
- archibate/mallocvis
- archibate/reflect-hpp
- archibate/debug-hpp
- archibate/hermes
- archibate/genius.nvim
- LanbingIce/IsaacSocket-Utility
- archibate/qdanmu
- zenustech/zeno3-poc
- archibate/minilog
- archibate/threebody-example
- archibate/babyjson-demo
- taichi-dev/taichi_three
- taichi-dev/taichi_blend
- taichi-dev/taichi.js
- archibate/ptina
- zenustech/zenoblend
- archibate/NBodySolver
- archibate/vue-class-manage-system
- archibate/facereco
- archibate/jsp-chess
- archibate/pysobol
- archibate/newos
- archibate/poczfx
- archibate/logisim
- archibate/newton
- archibate/vimrc

## GCC 建议开启的警告选项

```
-Wall -Wextra -Weffc++
-Werror=uninitialized
-Werror=return-type
-Wconversion -Wsign-compare
-Werror=unused-result
-Werror=suggest-override
-Wzero-as-null-pointer-constant
-Wmissing-declarations
-Wold-style-cast -Werror=vla
-Wnon-virtual-dtor
```
