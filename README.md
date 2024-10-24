# Image-Processing-Algorithms

This repository contains Python implementations of basic image processing algorithms developed from scratch without using any external image processing libraries.

## Overview

The following algorithms are implemented:
1. **Nearest Neighbor Interpolation and Resizing** - Resize an image using Nearest Neighbor Interpolation.
2. **Bilinear Interpolation and Resizing** - Resize an image using Bilinear Interpolation.
3. **Convolution** - Apply a convolution operation to an input image with a specified kernel.
4. **Gaussian Filter** - Smooth an input image using a Gaussian filter.

## Algorithms Description

### 1. Nearest Neighbor Interpolation
The simplest interpolation technique that selects the closest pixel value to assign to the new pixel in the resized image. It’s fast but results in blocky images.

### 2. Bilinear Interpolation
This technique considers a weighted average of the four nearest pixel values to compute the new pixel value. It produces smoother results compared to nearest neighbor interpolation.

### 3. Convolution
Convolution is an operation that slides a small matrix called a kernel across an image and computes the weighted sum of the overlapping pixel values to produce a filtered image. This is commonly used for feature extraction.

### 4. Gaussian Filter
The Gaussian filter is used for image smoothing by reducing noise and detail. It applies a Gaussian function over the image and uses convolution to blur the image.

