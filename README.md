# DynOSeg: Dynamic Object Segmentation via Motion-Geometry Fusion

*Xu Han, Yiduo Wang, Yiran Wang, Viorela Ila*

Australian Centre for Robotics, School of Aerospace, Mechanical and Mechatronic Engineering, The University of Sydney

<!-- <a src="https://img.shields.io/badge/cs.CV-2605.30352-b31b1b?logo=arxiv&logoColor=red" href="https://arxiv.org/abs/2605.30352">
<img src="https://img.shields.io/badge/cs.CV-2605.30352-b31b1b?logo=arxiv&logoColor=red"></a>
<a href="https://www.robots.ox.ac.uk/~vgg/research/gmos/" alt="Project page">
<img alt="Project page" src="https://img.shields.io/badge/project_page-gmos-blue"></a>

&nbsp;

<p align="center">
  <img src="resources/teaser.png" width="900"/>
</p> -->

## Visualization

<table align="center" width="100%">
  <tbody>
    <tr>
      <th colspan="4" align="center">DAVIS2017-M</th>
    </tr>
    <tr>
      <td align="center" width="25%">
        <img src="assets/demo1.gif" alt="DynOSeg visualization example 1" width="100%" />
      </td>
      <td align="center" width="25%">
        <img src="assets/demo2.gif" alt="DynOSeg visualization example 2" width="100%" />
      </td>
      <td align="center" width="25%">
        <img src="assets/demo3.gif" alt="DynOSeg visualization example 3" width="100%" />
      </td>
      <td align="center" width="25%">
        <img src="assets/demo4.gif" alt="DynOSeg visualization example 4" width="100%" />
      </td>
    </tr>
    <tr>
      <th colspan="4" align="center">KITTI</th>
    </tr>
    <tr>
      <td align="center" colspan="2" width="50%">
        <img src="assets/demo5.gif" alt="DynOSeg visualization example 5" width="100%" />
      </td>
      <td align="center" colspan="2" width="50%">
        <img src="assets/demo6.gif" alt="DynOSeg visualization example 6" width="100%" />
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2" width="50%">
        <img src="assets/demo7.gif" alt="DynOSeg visualization example 7" width="100%" />
      </td>
      <td align="center" colspan="2" width="50%">
        <img src="assets/demo8.gif" alt="DynOSeg visualization example 8" width="100%" />
      </td>
    </tr>
  </tbody>
</table>

## Model Architecture

<img src="assets/arc.png" alt="DynOSeg model architecture" width="100%" />

**Overview of the proposed DynOSeg framework.**
DynOSeg computes a residual map from depth, camera poses, and optical flow.
Dedicated encoders process the depth and residual maps, while a frozen DINOv2 encoder extracts high-level semantic features from the RGB image.
Geometry-Aware Spatial Fusion (GSF) and Global–Local Semantic-Aware Fusion (GLSF) integrate these multimodal features. A segmentation decoder then produces moving-object masks from the fused representation.


## Installation & Usage


The reference hardware and software environment is listed below:


<table align="center">
  <thead>
    <tr><th>Component</th><th>Specification</th></tr>
  </thead>
  <tbody>
    <tr><td>Operating system</td><td>Ubuntu 24.04.4 LTS (Noble Numbat)</td></tr>
    <tr><td>GPU</td><td>NVIDIA GeForce RTX 4090</td></tr>
    <tr><td>NVIDIA driver</td><td>580.159.03</td></tr>
    <tr><td>NVCC Compiler</td><td>V12.8.61</td></tr>
  </tbody>
</table>


**The code is comming soon!**

