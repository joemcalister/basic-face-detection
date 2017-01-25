# basic-face-detection
Basic face detection using C++ and OpenCV 3.0.

## How to compile
You must have OpenCV 3.0 installed, easiest to use CMake to compile.
```Shell
cmake .
make
```

## How to run
```Shell
./facedetect
```

## Parameters to change
You must add the path to a valid Haar file within the main.cpp file, this file is easy to find online. Multiple versions exist for specific face positions. You also need to add the path to a valid image to analyse.