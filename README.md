# FlappyTiger
The flappybird clone you definately dont need. This is my first game written in C++ using glfw.


## Building
Linux:
```
git clone --recurse-submodules https://github.com/Tigermouthbear/flappytiger.git
cd flappytiger
mkdir build && cd build
cmake ..
make
```
Other:
```
Steps not provided, but it should build on other systems too
```

## Installing (Linux)
Linux:
```
git clone --recurse-submodules https://github.com/Tigermouthbear/flappytiger.git
cd flappytiger
mkdir build && cd build
cmake -DINSTALL_APP=ON ..
make
sudo make install
```
