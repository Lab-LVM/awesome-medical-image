- Title : UNETR: Transformers for 3D Medical Image Segmentation
- Publication : IEEE, 2022
- Link : [[paper]](https://arxiv.org/abs/2103.10504) [[code]](https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV)


### Abstract
- Problem : 3D medical Image Segmentation
- Solution : the task of volumetric (3D) medical image segmentation as a sequence-to-sequence prediction problem.
  - with `Vision Transformer`
- Results : n BTCV dataset, UNETR achieves new state-of-the-art performance on both Standard and Free Competition sections on its leaderboard.
- Method : They utlize both `Transformer` and `CNN` architecture in the U-Net architecture.
    - They use transformers in the encoder. 
    - The extracted representations from the transformer encoder are merged with the CNN-based decoder via skip connections at multiple resolutions.
 
![image](https://user-images.githubusercontent.com/35554144/213899244-8a521176-3987-432e-a87d-026ef6c85c6a.png)

### References
```
@inproceedings{hatamizadeh2022unetr,
  title={Unetr: Transformers for 3d medical image segmentation},
  author={Hatamizadeh, Ali and Tang, Yucheng and Nath, Vishwesh and Yang, Dong and Myronenko, Andriy and Landman, Bennett and Roth, Holger R and Xu, Daguang},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={574--584},
  year={2022}
}
```
