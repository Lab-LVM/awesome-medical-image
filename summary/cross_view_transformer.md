# Cross-View Transformer

- Title: Multi-view Analysis of Unregistered Medical Images Using Cross-View Transformers

- Publication: MICCAI, 2021

- Link: [[paper](https://arxiv.org/pdf/2103.11390)] [not available]

  

## Abstract

- Problem: Multi-view medical image analysis
- Solution: Novel cross-view transformer method to transfer information at the level of spatial feature maps.
- Result: 80.3 (%) AUC on CBIS-DDSM, 83.4 (%) AUC on CheXpert
- Method: The proposed method could be summarized into 2 parts.

  - Cross-view transformer: Q(target), K,V(source) cross attention
- Token-based attention: Reduce the number of source tokens to the small integer R by using a weight matrix.



![image](https://user-images.githubusercontent.com/31476895/210289653-1bf9506e-7055-407d-b359-5399078ea593.png)



## Reference

```tex
@inproceedings{tulder2021multi,
  title={Multi-view analysis of unregistered medical images using cross-view transformers},
  author={Tulder, Gijs van and Tong, Yao and Marchiori, Elena},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={104--113},
  year={2021},
  organization={Springer}
}
```



