---
layout: project
type: project
image: img/PelagicPixels.png
title: "Pelagic Pixels"
date: 2024-12-12
published: true
theme: jekyll-theme-architect
labels:
  - Marine Conservation
  - Synthetic Data
  - AI Training
---
<br>

## &ensp; &ensp; &ensp; [<ins style="color: black">Organization Page</ins>](<https://universityofhawaii.edu/>)&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;[<ins style="color: black">Project Repository</ins>](<https://github.com/uhmanoa/pelagic-pixels>)&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;[<ins style="color: black">Project Page</ins>](<https://universityofhawaii.github.io/#pelagicpixels>)

<br>

## Purpose
Pelagic Pixels is a synthetic data generation pipeline aimed at addressing the scarcity of real-world data for marine object detection. It combines 3D model animations with real-world footage to train AI models for identifying rare and protected marine species, such as sea turtles, rays, and sharks, in an ethical and scalable manner.

<br>

## Milestones
The Pelagic Pixels project is structured into milestones focusing on various aspects of the data generation pipeline and its application.

<br>

## [<ins style="color: black">M1</ins>](https://github.com/orgs/uhmanoa/projects/1)
Focused on building the synthetic data generation pipeline, including 3D model acquisition, animation, and integration with underwater footage.

<br>

## [<ins style="color: black">M2</ins>](https://github.com/orgs/uhmanoa/projects/2)
Expanded the dataset with randomized augmentations for model placement, size, lighting, and color adjustments to enhance realism and variability.

<br>

## [<ins style="color: black">M3</ins>](https://github.com/orgs/uhmanoa/projects/3)
Instrumented the pipeline with automated annotations for YOLOv5 training, conducted testing, and documented findings on the synthetic-to-real domain gap.

<br>

## Dataset
The dataset comprises 1,600 synthetic images annotated for species detection tasks:
- **Training set**: 1,280 images
- **Validation set**: 320 images

Annotations include bounding boxes and species labels, formatted for compatibility with YOLOv5. Environmental diversity and species representation are key features.

<br>

## Features
- **Ethical Data Collection**: Utilizes 3D models and public footage, eliminating the need for intrusive real-world data collection.
- **Augmentation**: Integrates realistic variations in lighting, orientation, and size for robust AI training.
- **Scalability**: Enables large-scale dataset generation for rare marine species.

<br>

## Results
Initial testing with YOLOv5 highlighted limitations in detecting real-world marine species due to synthetic-to-real domain gaps. Future improvements include advanced blending techniques and domain randomization.

<br>

## Contribution
I focused on developing the augmentation module of the pipeline, including:
- Randomizing lighting, color, and size adjustments to enhance realism.
- Integrating species-specific animations with underwater footage.
- Interpolation of these animations over both live and static footage.

This role involved both technical development and ensuring alignment with ethical data collection standards.

<br>
