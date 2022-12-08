# Readme

COMS 4995 006 Deep Learning for Computer Vision - Final Project

Deep Learning for Monocular Depth Prediction

Yue Kuang (yk2951@columbia.edu)

## Description

The objective of this project is to implement a deep learning system that can predict the depth of each pixel. It should map a $H\times W\times 3$ image to a $H\times W\times 1$ depth map. Starting with a self-developed convolutional autoencoder, we also reproduced more complex models such as U-Net with skip connection from scratch. We also tried applying transfer learning where we replace the encoder part with large pre-trained models such as Xception and DenseNet.

Quantitative evaluations will be performed on different model architectures we implemented. We compare the performance of models and we confirm the superiority of combining pre-trained models with decoder, which brings to the improvement of model performances in monocular depth prediction tasks.

![Demonstration](https://github.com/kySheryl/Monocular_Depth-Prediction/blob/main/result.png)

## Sources

* Source code: [GitHub](https://github.com/kySheryl/Monocular_Depth-Prediction).
* Report: [Drive](https://drive.google.com/file/d/1QdNO7_ODcYgqMkundIMso1Cf99aWWLls/view?usp=sharing) or [GitHub](https://github.com/kySheryl/Monocular_Depth-Prediction/blob/main/Monocular_Depth_Prediction.pdf)

