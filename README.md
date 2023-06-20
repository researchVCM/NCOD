# NCOD: Near-Optimum Video Compression for Object Detection Dataset

This repository contains the dataset presented in the "Near-Optimum Video Compression for Object Detection" paper, which appeared in ISCAS 2023.\
The dataset is designed to support research and experimentation in the field of video compression and video compression for machines. You can access the values of important features, such as VCA, SITI, etc., and the result of performing the YOLOv4 object detection model on the videos in the [SFU-HW-Objects-v1](https://www.sciencedirect.com/science/article/pii/S2352340920315808) dataset.

## Dataset Contents

The dataset comprises the following components:

1. **Features:** This folder contains feature files extracted from video frames. There are two categories: "Frame Level" which contains the extracted features from each frame, and the "Sequence Level" which comprises the pooled features of individual frames to represent a sequence. 
    The features are VCA, AGH, SITI, CAMBI, and Quat.

2. **Object Detection Results:** This folder includes the object detection result. Each video has a CSV file representing the metrics, such as precision, recall, etc., for each X265 CRF value. For example, the "BQMall_832x480_60_0to100.csv" file is associated with the first 100 frames of the video "BQMall_832x480_60" in the SFU-HW-Objects-v1 dataset.
