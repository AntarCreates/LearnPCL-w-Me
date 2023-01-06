# LearnPCL-w-Me
TL;DR: This repository is a collection of what I learned about point cloud processing.

Many many moons ago I had created a repository on "Big bot" which is a six-wheeled robot used to generate a 3D map simulation of a V-shaped cave structure.
If you are interested, the respository can be found here - https://github.com/AntarCreates/big_bot_description


In the demo, we looked at how to create a 3D map and how to visualize it. Now, let's take things a step further and explore some advanced techniques for enhancing our 3D mapping. There are many ways we can do this, and in this repository, we'll delve into some of the most effective ones. So, are you ready to take your 3D mapping skills to the next level? Let's get started!

*Note: I highly recommend you use Jupyter Notebbok using the VS Code extension for the examples, especially if you are just starting like me :)*

## Lesson 1: PCL Segmentation with RANSAC and DBSCAN

Notebook: cave_pcl_segmentation.ipynb

In this notebook we take this, which is the octomap of a segment of the V-shape cave [ I took one arm of the V ] in depth[Z-axis]-based segmentation-

[Screencast from 7-1-23 02:30:30 পূর্বাহ্ণ +06.webm](https://user-images.githubusercontent.com/81281780/211096601-45dcd330-478d-4997-92ed-9eb48975d4b4.webm)

to this, which is a more generalistic and desired segmentation via Eucldean clustering  -


https://user-images.githubusercontent.com/81281780/211097018-b35cd1e0-4229-46e4-9362-ee36b4996615.mp4
