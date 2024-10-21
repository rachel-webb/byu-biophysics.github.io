---
layout: page
title: Kaggle Competition
description: Detect and label flagellar motors in 3D images of various bacteria.
img: assets/img/bacteria.jpg
importance: 1
category: ImageAI
related_publications: true
---

# Locating Biomolecular Nanomachines 


## Overview
In this competition, you’ll create machine-learning algorithms capable of identifying and locating flagellar motors in 3D images of various bacteria. The data set is comprised of ~750 3D bacterium images that may or may not contain a flagellar motor. The images have a low signal-to-noise ratio due to the microscopic nature of the bacteria. 

## Description
Bacteria are powerful, unique organisms that play a significant, and sometimes deadly, role in human life. Understanding the nanomachines that power bacteria is critical to developing effective drugs and improving disease research. 

A powerful way to understand these nanomachines is to know what they look like. Scientists use electron microscopes to image bacteria frozen in a lifelike state from different angles. These images are then reconstructed into complete 3D images known as tomograms. Despite a low signal-to-noise ratio, these tomograms can provide near-atomic resolution of nanomachines.

Though much of the imaging process is automated, a significant bottleneck in the identification of these nanomachines is the manual segmenting (separating a tomogram into the important structures within a bacterium) and labeling process. 

This competition challenges you to create an algorithm that can differentiate between bacteria with and without flagellar motors, nanomachines that control flagella and allow the bacteria to turn and swim. Your algorithm will then accurately identify where the motors are, if applicable. Your efforts will significantly reduce the time spent identifying microscopic structures in bacteria, thus accelerating scientific research that can lead to improved drug development and disease research. 

## Possible Approaches 
Lots of existing technologies are available for use to help with this problem, and we encourage you to use as many resources as possible. Some resources that we have used include the following: 

-	Automatic particle pickers (ex., DeepET Picker)
-	Segment Anything Model (SAM)
-	Ray features
-	Template matching
-	YOLO and other neural networks 

Our first two community Kaggle competitions used datasets of 2D slices of tomograms to identify the flagellar motors, and participants used a variety of data augmentation techniques and object detection algorithms to classify and predict motor location within each image. 

## Acknowledgements
Our efforts are supported by a grant from the Chan-Zuckerberg Initiative (CZI). We’d like to thank Grant Jensen and his lab, which has supplied us with ~40,000 tomograms to sort through for our data set. We’d also like to note that the Jensen lab has been working with CZI to create a cryo-electron tomography portal, where researchers can publicly upload and access tomograms to enhance world-wide cooperativity. 

Lastly, we’d like to thank Kaggle for believing in this problem, supplementing our prize pool money, and allowing us to reach members of the machine learning and computer vision communities.

  