# CS419: Digital Image and Video Analysis
## Introduction 
This course provided a comprehensive introduction into digital image & video processing and analysis. Major topics were:
1. Image acquisition
2. Linear and non-linear filtering
3. Content description
4. Video analysis

This course was offered by [Prof. Erchan Aptoula (Erhan Abdullah)](https://sites.google.com/view/erchan-aptoula/) at [Sabanci University](https://sabanciuniv.edu/en) during the 2024-2025 Fall semester.

In the rest of this _README_ file, you can find links for extra studying material and resources that can be helpful for the enthusiasts. It is important to note that all the links were originally provided by Prof. Aptoula himself. **I do not** claim any ownership over these documents/websites. 

---

## Textbooks
- Digital Image Processing by Gonzales and Woods
- Digital Image Processing by W. K. Pratt (more technical)
- Image Processing: the fundamentals by Petrou and Petrou (a more signal processing oriented perspective, suitable for EE students)
- Introduction to mathematical morphology
- Morphological Image Analysis by Pierre Soille (the reference book of MM)
- Computer Vision by Szeliski (reference book for classic computer vision)

> **NOTE:** You can find the original versions of these books on various platforms, and purchase them yourself.

---

## Week 1
### Reading
- From Digital Image Processing of Gonzalez and Woods: Chapter 1 and Chapter 2: 2.1, 2.2, 2.3, 2.4
- The"Digital Image Processing" book of William K. Pratt is a bit more advanced for those of you who need a more in-depth coverage of these concepts.

### Python Related Tutorials
Video tutorials by [Hasan Alp Boz](https://tr.linkedin.com/in/hasan-aboz), all of which require a Sabanci email address to be viewed:
- [Introduction to Colab](https://drive.google.com/file/d/19g2NuDq9sOLzTm730XyG3EIIqu1GoFOD/view)
- [Working with Datasets in Colab](https://drive.google.com/file/d/1wVl8cnJ-floTDg0z6mFxIPPEb5T4uFEZ/view)
- [Notes on Python](https://drive.google.com/file/d/1YayrDTOMmzpV7MmK076xqUeIHT8TNZSw/view) 

Other tutorials, which are publicly available:
- [Google's Python class](https://developers.google.com/edu/python/)
- [python/numpy tutorial](https://compsci682.github.io/notes/python-numpy-tutorial/) from COMPSCI 682 by [Justin Johnson](https://cs.stanford.edu/people/jcjohns/)
- [jupyter tutorial](https://compsci682.github.io/notes/jupyter-tutorial/) from COMPSCI 682
- [GoogleColab tutorial](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d) on Medium by [Fuat](https://medium.com/@fuatbeser)

> **NOTE:** At the time of making this, these videos were stored on a Google Drive folder. They might have been removed by the time you're seeing this. Also, only users with a valid `@sabanciuniv.edu` Gmail account can access these due to strict sharing settings. 

### Math Brushup
All the resources below have been suggested to be studied prior to the class:
- [Vectors](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) by 3blue1brown
- [Linear transformations and matrices](https://www.youtube.com/watch?v=kYB8IZa5AuE&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=3) by 3blue1brown
- [Bayes Theorem](https://www.youtube.com/watch?v=R13BD8qKeTg) by Veritasium  
- [Linear algebra review](https://www.youtube.com/watch?v=EpNr7ODVW-A&list=PLb0Gp98iu3OyGIWG2gk7VE0DJ4cDNWb6E) by Andrew Ng

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/1_simple_grayscale_image_processing_operations.ipynb) on simple operations with grayscale images.

> **NOTE:** All the notebooks regarding this course have been provided by Prof. Aptoula and the Teaching Assistants (TA) of this course. All credit goes to them. You can find the notebooks in the `notebooks` folder of this repository, or [this link](https://github.com/KouroshKSH/CS419-Resources/tree/master/notebooks).

---

## Week 2
### Reading
From Digital Image Processing of Gonzalez and Woods: 3.1, 3.2, 3.3 and 3.4

### Python Related Tutorials
- [Official Python Opencv tutorials](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html) (check out core operations for this week)
- Unofficial tutorials: [GeeksForGeeks](https://www.geeksforgeeks.org/opencv-python-tutorial/) and [TutorialsPoint](https://www.tutorialspoint.com/opencv_python/index.htm)
- [Unofficial tutorial video for python-opencv](https://www.youtube.com/watch?v=oXlwWbU8l2o&ab_channel=freeCodeCamp.org&themeRefresh=1) by `freeCodeCamp.org`

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/2_point_processing.ipynb) on point processing.

### This Week's Question
During class, this question was asked by a student:
> "Is rotation shift invariant?"

To which, Prof. Aptoula answered:
> "No."

The visual below explains why:
![screenshot of week 2's answer](https://github.com/KouroshKSH/CS419-Resources/blob/master/images/Screenshot%20-%20week%202%20-%20rotation%20shift%20invariant.png)

> **NOTE:** [This image](https://github.com/KouroshKSH/CS419-Resources/blob/master/images/Screenshot%20-%20week%202%20-%20rotation%20shift%20invariant.png) can also be found in the [images](https://github.com/KouroshKSH/CS419-Resources/tree/master/images) folder of this repository. 

---

## Weeks 3 and 4
### Reading
- From Digital Image Processing of Gonzalez and Woods Sections 9.1 to 9.5
- Chapters 1-5 from Morphological Image Processing, P. Soille.

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/3_binary_image_analysis.ipynb) on binary image analysis.

---

## Week 5
### Reading
From Digital Image Processing of Gonzalez and Woods Sections 3.4 to 3.6

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/4_spatial_domain_linear_filtering.ipynb) on linear image processing for spatial domain.

---

## Week 6
### Reading
- From Digital Image Processing of Gonzalez and Woods Chapter 4
- From Pratt's book: chapters 8 and 9 for an indepth coverage of image transforms (optional).

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/5_frequency_domain_linear_filtering.ipynb) on linear image processing for frequency domain.

---

## Week 7
### Reading
- From Digital Image Processing of Gonzalez and Woods Section 9.6
- From Pratt's book: 14.6
- From Soille's morphological image analysis: chapters 6 and 8

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/6_graysacale_morphology.ipynb) on mathematical morphology for grayscale images.

---

## Week 8
### Reading
- From Digital Image Processing of Gonzalez and Woods Chapter 6 (required)
- From Pratt's book: chapter 3 for a more in-depth coverage (optional)

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/7_color_image_processing.ipynb) on color-based image processing.

---

## Week 9
### Reading
- From Digital Image Processing of Gonzalez and Woods Chapter 10 (required)
- From Szeliski's book: Section 7.5 (optional)

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/8_image_segmentation.ipynb) on image segmentation.

---

## Weeks 10 and 11
### Reading
From Digital Image Processing of Gonzalez and Woods Chapter 11 [required]

### Videos
- [Image classification using gray-level co-occurrence matrix (GLCM) features and LGBM classifier](https://www.youtube.com/watch?v=5x-CIHRmMNY) by [DigitalSreeni](https://www.youtube.com/@DigitalSreeni) on YouTube
- [how are the Local Binary Pattern (LBP) values calculated?](https://www.youtube.com/watch?v=h-z9-bMtd7w&list=PLVLAu9B7VtkbmfbamE0kRutTMbPTlCYyM) by [Ritika xRay Pixy](https://www.youtube.com/@RitikaxRayPixy) on YouTube

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/9_image_description.ipynb) on image descriptors.

---

## Week 12
### Reading
I highly recommend the following books (all available online - one way or another), they all have convnet specific chapters that I suggest reading.

- [Understanding Deep Learning](https://udlbook.github.io/udlbook/)
- [The Deep Learning Book](https://www.deeplearningbook.org/) by Ian Goodfellowm, Yoshua Bengio and Aaron Courville
- [Dive into deep learning](https://d2l.ai/), an interactive deep learning book with code, math and discussions
- [Practical Machine Learning for Computer Vision](https://github.com/GoogleCloudPlatform/practical-ml-vision-book) by [Google Cloud Platform](https://github.com/GoogleCloudPlatform), for those of you preferring Keras+Tensorflow

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/10_texture_image_descriptors.ipynb) on image descriptors for texture.

### Blogs/videos/tutorials

- [Google Playground Exercises](https://developers.google.com/machine-learning/crash-course/neural-networks/interactive-exercises) for Neural Networks
- [Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) playlist by [3blue1brown](https://www.youtube.com/@3blue1brown) on YouTube
- [CS231n Stanford notes](https://cs231n.github.io/neural-networks-1/) on Convolutional Neural Networks for Visual Recognition
- [Convolution in Image Processing](https://www.youtube.com/watch?v=8rrHTtUzyZA), presented by [3blue1brown](https://www.youtube.com/@3blue1brown) on [The Julia Programming Language](https://www.youtube.com/@TheJuliaLanguage)'s YouTube channel
- Andrew Ng [slides](https://cs230.stanford.edu/files/C4M1.pdf) on CNNs & [videos](https://www.youtube.com/watch?v=2-Ol7ZB0MmU&list=PLFKog8qYYq0HOfk3EIYyg6O1008OebB5t) on YouTube

---

## Week 13
### Reading
- [Object detection algorithms](https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e) on Medium
- [Guide to object detection](https://www.v7labs.com/blog/object-detection-guide) by [V7 Labs](https://www.v7labs.com/)
- [Object Detection Guide](https://viso.ai/deep-learning/object-detection/) by [Viso AI](https://viso.ai/)
- [Image Segmentation with Deep Learning](https://viso.ai/deep-learning/image-segmentation-using-deep-learning/) by Viso AI
- [Image Segmentation: Traditional vs. Deep Learning Techniques](https://www.v7labs.com/blog/image-segmentation-guide) by V7 Labs
- _Image Segmentation Using Deep Learning: A Survey_ [paper](https://arxiv.org/pdf/2001.05566) by Minaee et. al., 2020
- [Instance Segmentation: Comprehensive Guide](https://www.basic.ai/blog-post/instance-segmentation-in-2024) blog by [Basic AI](https://www.basic.ai/)
- [Objection Detection Articles](https://github.com/amusi/awesome-object-detection) by [Amusi](https://github.com/amusi) on GitHub
- [Semantic Segmentation Links](https://github.com/mrgloom/awesome-semantic-segmentation) by [mrgloom](https://github.com/mrgloom) on GitHub 
- [Open MMDetection](https://github.com/mrgloom) repository by [OpenMMLab](https://openmmlab.com/) on GitHub; a nice framework for instance segmentation

### Notebook
A [notebook](https://github.com/KouroshKSH/CS419-Resources/blob/master/notebooks/11_image_classification_using_cnn.ipynb) on image classification using CNNs.

---

# ATTENTION!
All of these links have been provided by Prof. Aptoula during the semester. They have been provided as _extra studying material_ for the students of the course CS419. No one claims any ownership rights over the distributed material besides the one created by Prof. Aptoula himself or his teaching assistants. All sources have been cited and credited accordingly. 


---
