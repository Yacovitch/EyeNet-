# EyeNet++: A Multi-Scale and Multi-Density Approach for Outdoor Point Cloud Semantic Segmentation

## Overview
EyeNet++ is a novel semantic segmentation network designed for outdoor 3D point cloud datasets. Inspired by the human vision field, EyeNet++ introduces a multi-scale and multi-density input framework combined with parallel processing architecture. These innovations enable enhanced coverage and accurate feature extraction for dense point cloud data.

### Key Features:
- **Multi-Scale and Multi-Density Input Scheme**: Captures diverse spatial features using dense central and sparse peripheral regions.
- **Dense Local Feature Aggregation (DLFA)**: Efficiently extracts contextual information from objects of varying sizes.
- **Connection and Feature Merging Blocks**: Facilitate effective exchange and integration of features across multi-scale inputs.
- **Proven Performance**: Demonstrated state-of-the-art results on benchmark datasets such as SensatUrban, Toronto3D, and YUTO Semantic.

## Status
The source code for EyeNet++ and pre-trained models will be released soon. Stay tuned for updates!

## Datasets
EyeNet++ has been extensively evaluated on several large-scale datasets:
- [SensatUrban](https://github.com/QingyongHu/SensatUrban)
- [Toronto3D](https://github.com/Toronto3D/Toronto3D)
- [YUTO Semantic]((https://huggingface.co/datasets/ausmlab/yuto-semantic))
- [DALES](https://github.com/DALES/DALES)
- [Semantic3D](http://www.semantic3d.net/)

## Upcoming Release
The GitHub repository will include:
1. Implementation code for EyeNet++ in TensorFlow.
2. Pre-trained models for easy reproducibility.
3. Training and evaluation scripts.
4. Documentation to guide users through setup and usage.

## Citation
If you find this work helpful, please cite:
