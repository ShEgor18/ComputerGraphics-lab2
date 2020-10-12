# Computer graphics: Visualization of tomograms

## Introduction

Tomography is obtaining a layer-by-layer image of the internal structure of an object.
Most often, but not always, the object of tomographic studies are living tissues.
Tomography data is a three-dimensional array of voxels - elements of a three-dimensional regular grid. 
Each voxel contains one density value, usually of type short or ushort.
Transfer Function (TF) is used to convert the density value to color. 
Transfer Function can be gray, black to white, or color, linear or non-linear.
In this lab we will use a linear TF from black to white, since it is very simple to create, all values are calculated by the formula:

intensity = (x − min)\(max − min) ∗ 255

## Tasks to complete:

- Change Transfer Function;
- Rendering with QuadStrip;
