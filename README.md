# MazeVisibility
#### Jun-Yu (Andrew) Chen
## Introduction
Implementation of a maze rendering program, which is not too far removed from those used in computer games of the first-person variety. Clipping, Projecting and Recursive Visility are implemented without using calculation functions provided by OpenGL.
<p align="center">
  <img src="https://user-images.githubusercontent.com/64970325/151764120-b7b930ec-ee6e-4cfb-a42c-40a44f164a82.png" />
</p>

## Building and Running
Can be built directly with CMake with the given CMakeLists text file, preferred building/running platform would be Visual Studio 2019 on Windows 10.

## Tasks Done
1. Projecting a wall onto the screen with perspective projection and drawing it.
2. Correctly clipping walls to the view for a single cell maze.
3. Visibility calculated recursively.
##### All calculation functions mentioned above are implemented single-handedly without using OpenGL calls.


## Implementation
Done as coursework for CS3026 Introduction to Computer Graphics in NTUST, Fall 2021. More details about the course project could be seen in [this link](http://dgmm.csie.ntust.edu.tw/?ac1=courprojdetail_CG2012F_3&id=5ecf8d85e9b81&sid=614a94d120c83).

