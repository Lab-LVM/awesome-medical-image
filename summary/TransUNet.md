# TransUNet

- Title: TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation
- Publication: arXiv preprint arXiv:2102.04306
- Link: [[paper](https://arxiv.org/pdf/2102.04306v1.pdf)] [[code](https://github.com/sthalles/SimCLR)]

## Abstract

- Task: Apply Transformer to medical image task


- Keywords
  - CNN-Transformer hybrid as encoder
  - Cascaded Upsampler (CUP)


- Result: Achive better performance than FCN-based methods, CNN Self-attention methods on medical image segmentation task

- Methods
  - Transformer as Encoder
  - Patch Embedding
  - U-shaped upsampling with Skip connection

- Architecture


  <img width="643" alt="스크린샷 2023-01-10 오후 3 55 54" src="https://user-images.githubusercontent.com/42484578/211483038-d2860cd2-0734-46c1-b90b-641d5992f6b3.png">





## Reference

```
@inproceedings{chen2021transunet,
  title={TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation},
  author={Chen, Jieneng and Lu, Yongyi and Yu, Qihang and Luo, Xiangde and Adeli, Ehsan and Wang, Yan and Lu, Le and Yuille, Alan L., and Zhou, Yuyin},
  journal={arXiv preprint arXiv:2102.04306},
  year={2021}
}
```
