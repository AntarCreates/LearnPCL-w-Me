# LearnPCL-w-Me
TL;DR: This repository is a collection of what I learned about point cloud processing.

Many many moons ago I had created a repository on "Big bot" which is a six-wheeled robot used to generate a 3D map simulation of a V-shaped cave structure.
If you are interested, the respository can be found here - https://github.com/AntarCreates/big_bot_description


In the demo, we looked at how to create a 3D map and how to visualize it. Now, let's take things a step further and explore some advanced techniques for enhancing our 3D mapping. There are many ways we can do this, and in this repository, we'll delve into some of the most effective ones. So, are you ready to take your 3D mapping skills to the next level? Let's get started!

*Note: I highly recommend you use Jupyter Notebbok using the VS Code extension for the examples, especially if you are just starting like me :)*

## Lesson 1: PCL Segmentation with RANSAC and DBSCAN

Notebook: cave_pcl_segmentation.ipynb

In this notebook we take the .xyz file derived from an octomap of a segment of the V-shape cave [ I took one arm of the V ] in depth[Z-axis]-based segmentation to this, to a more generalistic and desired segmentation via RANSAC and Eucldean clustering.


![pcl](https://user-images.githubusercontent.com/81281780/211139604-18d4307f-df7e-4dd3-a72c-ecabf9dd9379.gif)

