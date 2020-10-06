# Deep Soft Procrustes for Markerless Volumetric Sensor Alignment
An easy to use depth sensor extrinsics calibration method. It is integrated and being used in a robust [Volumetric Capture](https://vcl3d.github.io/VolumetricCapture/) system.

<!--
| [Project Page](https://vcl3d.github.io/StructureNet/) | [Paper](https://arxiv.org/pdf/2003.10176.pdf) | ~~[Supplementary Material]~~ |
|:-----:|:------:|:------:|
-->
[![Paper](http://img.shields.io/badge/paper-arxiv.2003.10176-critical.svg?style=plastic)](https://arxiv.org/pdf/2003.10176.pdf)
[![Conference](http://img.shields.io/badge/IEEEVR-2020-blue.svg?style=plastic)](http://ieeevr.org/2020/)
[![Project Page](http://img.shields.io/badge/Project-Page-blueviolet.svg?style=plastic)](https://vcl3d.github.io/StructureNet/)

<img src="data/snapshot00.png" width="24%"> <img src="data/snapshot01.png" width="24%"> <img src="data/snapshot02.png" width="24%"> <img src="data/snapshot03.png" width="24%">

## Requirements
- Python 3.6.7
- [PyTorch 1.2 + cuda 9.2](https://pytorch.org/get-started/previous-versions/#v120)

## Installation
Run python install.py

**Important options**

`--input_path` : directory which contains depthmaps (in .pgm format)

`--output_path` : directory where results will be saved

`--scale` : multiplication factor that converts depthmap data to meters

`--saved_params_path` : path to the downloaded model

