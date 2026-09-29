# DAFM-JP-PCC

DAFM-JP-PCC implements a density-adaptive feature-modulation extension of JPEG Pleno Point Cloud Coding (JP-PCC) for LiDAR geometry compression.

The method uses a normalized block-occupancy descriptor to modulate the channel-wise features processed by the main analysis and synthesis transforms, while preserving the remaining JP-PCC coding pipeline and entropy model.

This repository contains the code, configuration files, training-dataset preparation tools, and evaluation scripts associated with the paper:

**Learned Geometry Compression of LiDAR Point Clouds with Density-Adaptive Feature Modulation**

The experiments include LiDAR-oriented retraining of JP-PCC, density-adaptive feature modulation, and comparisons with JP-PCC and MPEG G-PCC on the KITTI and Ford datasets.

## JP-PCC dependency

DAFM-JP-PCC is implemented as an extension of the JPEG Pleno Point Cloud Coding Verification Model. The original JP-PCC software is not redistributed in this repository and must be obtained separately from the official JPEG sources.
