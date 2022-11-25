# GAMES301 第二次作业

**The program , which runs in the Qt application, is used to load meshes and render using OpenGL.**


## Dependent External Libraries
* [Qt](https://www.qt.io/), Recommended version: 5.13.0
## Alternative External Libraries
* [Eigen](http://eigen.tuxfamily.org/)

## MAC下编译


```
cd Surface_Framework_Cmake
mkdir build && cd build
cmake .. -DCMAKE_PREFIX_PATH=/opt/homebrew/opt/qt5/
```

## Supported File Formats

.obj .off .ply .stl
