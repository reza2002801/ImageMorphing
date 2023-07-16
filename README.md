# Image Morphing Project

<p align="center">
  <img src="Studio_Project_V1.gif" alt="Project Demo" width="500" />
</p>
Image morphing is a mesmerizing process that morphs one image into another, generating a series of intermediate images that represent a gradual metamorphosis between the two images.

## 🚀 Overview 

Our Image Morphing project, combines **linear algebra** concepts and the **Delaunay Triangulation algorithm** for creating stunning image transitions. Delaunay Triangulation is a fascinating and efficient technique used to transform a set of points into a non-overlapping set of triangles. 

This scientific, yet artistic endeavour, operates on both **color** and **grayscale** images.

## 🛠️ Methodology 

Here's a step-by-step break down of our morphing procedure:

1. **Point Matching**: We begin with mapping points in the source image to the analogous points in the target image.

2. **Delaunay Triangulation**: Next, we leverage Delaunay Triangulation to transform the triangles in the source image to match the triangles in the target image. 

3. **Linear Algebra Transformation**: We then use linear algebra to complete the transformation, and create the intermediate images based on the calculated transformations.

4. **Sequence Generation**: Voila! We create a sequence of images, transitioning smoothly from the source image to the target image.

## 🎯 How To Use 

Usage is simple to allow your creativity to flow uninterrupted:

- Place your `initial` image (`res01.jpg`) and `final` image (`res02.jpg`) in the same directory as the script.

- Define the corresponding points in the two images and store them in `first.txt` and `second.txt` files, respectively. Every line hosts x and y coordinates, separated by three spaces.
