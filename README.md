# Visual Odometry

## Project Description

The main aim of this project is to calculate the visual odometry of the cars in the KITTI Dataset using Python and OpenCV. This notebook contains the following topics:

- Camera Coordinate system
- Projection matrix
- Disparity maps
- Depth map from Stereo Camera
- Depth from poinclouds
- SIFT (Scale Invariant Feature Transform)
- HOG (Histogram of Oriented Gradients)
- RANSAC (Random Sample Consensus)
- Visual Odometry

## Pre-requisites

- OpenCV
- Visual Odometry KITTI dataset (details can be found in the VO_example.ipynb)

## How to run the code

Run the VO_example.ipynb for demo. For detailed explanation follow visual_odometry.ipynb.

### Input: Stereo Image
<p align="center">
  <img src="https://github.com/ananyaverma2/visual_odometry/blob/master/images/gif1.gif" alt="animated" width="700" height="250"/>
</p>

### Output: Visual Odometry

The black lines indicate the ground truth whereas the red lines indicate the path calculated by us.

<p align="center">
  <img src="https://github.com/ananyaverma2/visual_odometry/blob/master/images/gif2.gif" alt="animated" width="600" height="300"/>
</p>

> This work is done by following the [video](https://www.youtube.com/watch?v=SXW0CplaTTQ&list=PLrHDCRerOaI9HfgZDbiEncG5dx7S3Nz6X) and the corresponding github [repository](https://github.com/FoamoftheSea/KITTI_visual_odometry).


