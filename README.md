# mesh-viewer

Implements a simple PLY viewer

![avatar](/arts/cow-toon.png)

## How to build

*Windows*

Open git bash to the directory containing this repository.

```
mesh-viewer $ mkdir build
mesh-viewer $ cd build
mesh-viewer/build $ cmake ..
mesh-viewer/build $ start mesh-viewer.sln
```

Your solution file should contain two projects: `mesh-viewer` and `test-ply-mesh`.
To run from the git bash command shell, 

```
mesh-viewer/build $ ../bin/Debug/test-ply-mesh.exe
mesh-viewer/build $ ../bin/Debug/mesh-viewer.exe
```

*macOS*

Open terminal to the directory containing this repository.

```
mesh-viewer $ mkdir build
mesh-viewer $ cd build
mesh-viewer/build $ cmake ..
mesh-viewer/build $ make
```

To run each program from build, you would type

```
mesh-viewer/build $ ../bin/mesh-viewer
```

## Demo of basic features

```
key N: view next model
key P: view previous model
```
![avatar](/arts/models.gif)

```
key S: view next shader
```
![avatar](/arts/shaders.gif)

```
mouse move: change direction of viewing

```
![avatar](/arts/directions.gif)

```
Shaders: normals
```
![avatar](/arts/normals.gif)
```
Shaders: phong-pixel
```
![avatar](/arts/phong-pixel.gif)

```
Shaders: phong-vertex
```
![avatar](/arts/phong-vertex.gif)

## Unique features 

```
Unique Shaders: toon
```
![avatar](/arts/cow-toon.gif)

```
key W: apply next texture
```
![avatar](/arts/textures.gif)
![avatar](/arts/apple.gif)
