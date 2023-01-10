# Swin-Unet
- Title: Unet-like Pure Transformer for Medical Image Segmentation
- Publication: MICCAI, 2021
- Link: [[paper](https://arxiv.org/pdf/2105.05537.pdf)] [[code](https://github.com/HuCaoFighting/Swin-Unet)]


## Abstract
- Problem: The need for pure-transformer architecture that can capture long-range dependency of medical image
- Solution: Propose U-shaped pure-transformer architecture for medical semantic segmentaion task
- Result: 79.13 average DSC on Synapse multi-organ CT, 90 average DSC on ACDC
- Architecture:
  1. Patch Partition and Linear Embedding Blocks - embedding the input images
  2. Swin Transformer Blocks - window attention
  3. Patch Merging Blocks - decreasing the resolution of feature maps and increasing the Channel(Dimension) of feature maps
  4. Patch Expanding - decreasing the Channel(Dimension) of feature maps and increasing the resolution of feature maps
<img width="469" alt="Screen Shot 2023-01-10 at 4 02 34 PM" src="https://user-images.githubusercontent.com/88542073/211483423-5b111095-12a6-4535-aa21-d79e46d95d09.png"> 
 
 ## Reference

 ```tex
 @inproceedings{cao2021swin,
  title={Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentation},
  author={Cao, H and Wang, Y and Jiang, D and Zhang, X and Tian, Q and Wang M},
  booktitle={},
  pages={},
  year={2021},
  organization={arXiv}
 }
