# HexBox: Interactive Box Modeling of Hexahedral Meshes

<p align="center"><img src="teaser.png"></p>

HexBox is an intuitive modeling method and interactive tool for creating and editing hexahedral meshes.
Hexbox brings the major and widely validated surface modeling paradigm of surface box modeling into the world of hex meshing.
This is the reference implementation of the paper

[***HexBox: Interactive Box Modeling of Hexahedral Meshes***]() </br>
F. Zoccheddu, [E. Gobbetti](https://www.crs4.it/peopledetails/8/enrico-gobbetti/), [M. Livesu](http://pers.ge.imati.cnr.it/livesu/), [N. Pietroni](https://www.nicopietroni.com), [G. Cherchi](http://www.gianmarcocherchi.com)</br>
_Computer Graphics Forum (SGP 2023)_.

## Setup

1. Clone this repository:

```Shell
git clone https://github.com/gcherchi/HexBox.git
cd HexBox
```

2. Generate the build system:

```Shell
mkdir build
cd build
cmake ..
```

3. Build:

```Shell
cmake --build .
```

4. Run the `gui` executable.

5. Enjoy! 😉

## Compatibility

Requires [CMake](https://cmake.org/) 3.14+, a modern C++20 compiler, OpenGL 2.0 support and an Internet connection.

Tested on MSVC v143 on Windows 11 and GCC 10 and Clang 14 on Ubuntu 22.10. 

> **NOTE:**  
> With this configuration Cinolib generates hundreds of warnings (OGDF might also generate some warnings on GCC). Compilation should succeed anyway; just ignore them.

> **NOTE:**  
> On Ubuntu, make sure to have `libgl1-mesa-dev`, `libglu1-mesa-dev` and `xorg-dev` installed.

## Cyting us

If you use HexBox for your project, please cite our paper with the following BibTeX entry: 

```bibtex
@article{hexbox2023,
  title   = {HexBox: Interactive Box Modeling of Hexahedral Meshes},
  author  = {Zoccheddu, F. and Gobbetti, E. and Livesu, M. and Pietroni, N. and Cherchi, G.},
  journal = {Computer Graphics Forum},
  year    = {2023},
  volume  = {},
  number  = {},
  pages   = {},
  doi     = {},
}
```