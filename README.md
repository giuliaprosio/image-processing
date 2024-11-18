# image-processing

This repository contains various projects of image processing and analysis, developed following the course "Bases du traitement d'image" of a.a. 2022/2023 at Sorbonne Université

Each folder contains a project with a step-by-step analysis of the methods useful to treat and analyze images.

## 1. Introduction to image enhancement
Go to the [project](./1_Intro_image_enhancement). The first work consists in an introduction to the use of python for pixel manipulation and image enhancement. 

## 2. Fourier analysis 
[Here](./2_Fourier_analysis/) the second project. The second practical work is dedicated to the study of the discrete Fourier transform applied to images and analyze the properties of the 
resulting spectrum.

## 3. 2D sample and aliasing 
[Here](./3_2D_sample_and_aliasing/) the third project. We have studied Fourier transform properties on 1D space. The results can be admitted in a 2-dimensional space too. 

The project studies the limit conditions of sampling of an image to avoid aliasing. 

## 4. Frequency filtering 
[Project 4](./4_Frequency_filtering/). The scope of this project is the study of possible alternatives to have convolutional filtering of images. 

## 5. Edge detection 
In [project 5](./5_Edge_detection/) we experiment with various edge detectors.
Particularly, we consider and study **Sobel filters** and **Laplacian filters**, putting into comparison First Order Detectors, which work on the gradient of an image, and Second Order Detectors, focused on the second derivative of the image. 

## 6. Harris corner detection 
[Project 6](./6_Harris_corner_detection/) is focused on the use of this powerful corner detector to process images. 
The Harris-Stephen's corners detectors computes a "corner response" matrix for each pixel based on the changes in intensity within a small window around the pixel, analyzing gradients in all directions. This way it is able to output the probable corners of an image. 

## 7. Split and merge
[Project 7](./7_Split_and_merge/) implements and tests the **split and merge** algorithm. This is a segmentation recursive algorithm used to split an image into heterogeneous regions. 

## 8. Search by content 
In [project 8](./8_Search_by_content/) we study the we develop a color based descriptor and then use it to find images the most similar to a color query. 
The descriptor is based on the HSV histograms and content query on similarity matrices between images in a database, each represented by an HSV descriptor. 

## 9-10. Face recognition
The objective of the [project 9-10](./9-10_Face_recognition/) work is to study the properties of eigenfaces face recognition method.

The Eigenfaces method is a technique for face recognition using principal component analysis (PCA). It transforms high-dimensional face images into a lower-dimensional subspace defined by eigenvectors, called eigenfaces, which capture the most significant features of facial variations.

Using this technique we are then able to test the recognition of faces in images and reconstruct specific faces from a dataset of images. 