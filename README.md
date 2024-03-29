# Image compression and decompression using PCA implemented from scratch

This repository shows how to use Principal Component Analysis (PCA) to compress both grayscale and colored images. The process includes compressing the images, visualizing the compressed versions, decompressing the images, and visualizing the reconstructed images. The implementation does not use built-in PCA functions and instead explores eigenfaces for compressing groups of images.


## Overview

- **Grayscale Image Compression and Decompression:**
  - Loads and resizes a grayscale image.
  - Applies PCA to compress the image.
  - Visualizes the original, compressed, and decompressed images.

- **Color Image Compression abd Decompression:**
  - Loads and resizes a color image.
  - Separates RGB channels and applies PCA to each channel.
  - Reconstructs the color image from compressed channels.
  - Visualizes the original, compressed, and decompressed color images.

- **Eigenfaces:**
  - Uses PCA on a `fetch_lfw_people` dataset from scikit-learn.
  - Extracts eigenfaces and compresses face images.
  - Visualizes original and decompressed face images.

## Results 

### Visualization of the original, compressed, and decompressed grayscale images.

![](images/GrayScaleoutput.png)

### Visualization of the original, compressed, and decompressed colored images.

![](images/Coloredoutput.png)


### Visualization of the first 5 Eigenfaces of an image to see how the initial components contain the most relevant information of the image.

![](images/First5EigenFacesoutput.png)

### Visualization of the original and decompressed of images in the `fetch_lfw_people` dataset.

![](images/EigenFacesoutput.png)
