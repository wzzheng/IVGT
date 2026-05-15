# IVGT: Implicit Visual Geometry Transformer for Neural Scene Representation
### [[Paper]]() [[Project]](https://wzzheng.net/IVGT/)

> Terra: Explorable Native 3D World Model with Point Latents

> [Yuqi Wu](https://ykiwu.github.io/)<sup>\*</sup>, [Tianyu Hu](https://github.com/ttt-y)<sup>\*</sup>, [Wenzhao Zheng](https://wzzheng.net/)<sup>*</sup>$\dagger$, [Yuanhui Huang](https://huang-yh.github.io/), [Haowen Sun](https://scholar.google.com/citations?hl=zh-CN&user=tGepc6EAAAAJ), [Jie Zhou](https://scholar.google.com/citations?user=6a79aPwAAAAJ&hl=en&authuser=1), [Jiwen Lu](http://ivg.au.tsinghua.edu.cn/Jiwen_Lu/)

<sup>*</sup> Equal contribution. $\dagger$ Project leader.

We propose IVGT, an implicit visual geometry transformer that learns a continuous neural scene representation from pose-free multi-view images in a single feedforward pass.
It captures coherent 3D geometry and appearance in a global canonical coordinate system, enalbing various downstream tasks including mesh reconstruction, novel-view synthesis, and surface estimation across diverse scenes.

![teaser](./assets/teaser.png)

## News.
- **[2026/5/18]** Paper released on [arXiv]().

## Overview
<p align = "center"> 
<img src="./assets/main.png" width="100%" />
</p>

Reconstructing coherent 3D geometry and appearance from unposed multi-view images is a fundamental yet challenging problem in computer vision.
Most existing visual geometry foundation models predicts explicit geometry by regressing pixel-aligned pointmaps, often suffering from redundancy and limited geometric continuity.
We propose IVGT, an Implicit Visual Geometry Transformer that implicitly model continous and coherent geometry from pose-free multi-view images.
This formulation learns a continuous neural scene representation in a canonical coordinate system and supports continuous spatial queries at any 3D positions, retrieving local features to predict signed distance (SDF) values and colors using lightweight decoders.
It allows direct extraction of continuous and coherent surface geometry, enabling rendering of RGB images, depth maps, and surface normal maps from arbitrary viewpoints.
We train IVGT via multi-dataset joint optimization with 2D supervision and 3D geometric regularization.
IVGT deonstrates generalization across scenes and achieves strong performance on various tasks including mesh and point cloud reconstruction, novel view synthesis, depth and surface normal estimation, and camera pose estimation.

## Getting Started
We will release the code soon.


## Citation
If you find this project helpful, please consider citing the following paper:
```

```

