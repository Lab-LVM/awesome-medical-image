# AnaXNet

- Title: Anatomy Aware Multi-label Finding Classicationin Chest X-ray

- Publication: MICCAI, 2021

- Link: [[paper](https://arxiv.org/pdf/2105.09937)] [not available]

  

## Abstract

- Problem: Failing to utilize important anatomical information.

- Solution: Propose a novel multi-label chest X-ray classification model that accurately classifies the image finding and also localizes the findings to their correct anatomical regions.

- Result: The proposed method outperforms state-of-the-art multi-label classification methods on the MIMIC-CXR image dataset.

- Method:

  1. Compute ROI using a Detection framework.

  2. Compute GCN ROI features using GCN.

  3. Cross attention ROI as q, v and GCN ROI as k.



![image](https://user-images.githubusercontent.com/31476895/210289308-594dc89e-e1c1-4ac7-9f69-ba617c2dde23.png)



## Reference

```tex
@inproceedings{agu2021anaxnet,
  title={Anaxnet: Anatomy aware multi-label finding classification in chest x-ray},
  author={Agu, Nkechinyere N and Wu, Joy T and Chao, Hanqing and Lourentzou, Ismini and Sharma, Arjun and Moradi, Mehdi and Yan, Pingkun and Hendler, James},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={804--813},
  year={2021},
  organization={Springer}
}
```



