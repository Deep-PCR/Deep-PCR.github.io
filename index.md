# Deep Learning-based Point Cloud Representation


The scope of this project is the design, development, implementation, and assessment of a DL-based static Point Cloud (PC) compressed representation targeting both decoding and enhancement consumptions.

The DL-based PC representation solutions will simultaneously accommodate compression efficiency and effective PC processing using the same compressed domain stream.

This work was funded by the Fundação para a Ciência e Tecnologia (FCT, Portugal) through the research project PTDC/EEI-COM/1125/2021, entitled “Deep Learning-based Point Cloud Representation”.



# About

Visual communications have a fundamental role in Human societies. In the digital era, this has led to the explosion of image and video-based applications and services, notably following the democratization of image and video acquisition, storage and streaming. However, conventional image and video-based experiences are far from the real-world immersion; this has motivated a rush for more realistic, immersive and interactive visual experiences, notably offering 6-DoF (Degrees-Of-Freedom) experiences where the user is free to exploit the six translational and rotational types of motion, possible in the real world.

The recent advances in visual data acquisition and consumption have led to the emergence of the so-called plenoptic visual models, where Point Clouds (PCs) are playing an increasingly important role. PCs are a 3D visual model where the visual scene is represented through a set of points and associated attributes, notably color (see Figure 1). To offer realistic and immersive experiences, PCs need to have millions, or even billions, of points, thus asking for efficient coding solutions.

![Figure_1](https://user-images.githubusercontent.com/124708731/232832937-53b8ec8a-cbdc-4bd7-87fd-3aa5b1c5a0ec.png)

Efficient and realistic immersive experiences are critical for emerging applications and services, notably virtual and augmented reality, personal communications and meetings, education and medical applications and virtual museum tours. This need has led the MPEG (Moving Picture Experts Group) standardization group to issued two PC coding standards; however, these standards are based on rather conventional technology, notably octree-based coding (G-PCC) and 2D image and video coding standards after 3D to 2D mapping (V-PCC).

Deep learning (DL)-based solutions are currently the state-of-the-art for multiple computer vision tasks, both high-level tasks and lower-level tasks, but also in the image coding domain, reaching competitive performance in a short time. 

The scope of this project is the design, development, implementation and assessment of a DL-based static PC compressed representation targeting both decoding and enhancement consumptions (see Figure 2). The proposed DL-based solutions will simultaneously accommodate efficient fidelity-to-original PC coding, with compression efficiency improvements over available solutions, and effective enhanced-from-original PC processing using the same compressed domain stream. 

![Figure_2](https://user-images.githubusercontent.com/124708731/232832884-b189fd97-0cbf-43f9-a192-5005ce8121ba.png)
