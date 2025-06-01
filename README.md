#### WISLNet | IEEE GRSL 2025 | HSI-CD
---
## Wavelet-Inspired Sparse Learning Network for Hyperspectral Image Change Detection

***Chengle Zhou, Zhi He, Jian Dong, and Liwei Zou***

*IEEE Geoscience and Remote Sensing Letters, vol. 22, pp. 1-5, May 2025*

---

![framework](https://github.com/chengle-zhou/MY-IMAGE/blob/b6823005846f3440eb968b1f6096c2ee54dd9f69/WISLNet/img-1.jpg =200x)

Fig. 1. Illustration of WTConv in the multiscale frequency domain.



## Abstract

In this letter, a novel wavelet-inspired sparse learning network (WISLNet) is proposed for hyperspectral image change detection (HSI-CD), which introduces wavelet convolution (WTConv) transform into a data-driven low-rank and sparse representation (LRSR) model to build a deep unfolding network in the frequency domain. The WISLNet mainly involves the following key steps. First, the difference image (DI) of the bitemporal hyperspectral images (Bi-HSIs) is obtained through pixel-by-pixel and band-by-band subtraction operations. Then, the LRSR model is designed as a deep unfolding network with modules for low-rank learning, sparse learning, and DI reconstruction to capture deep semantics related to change identification in the DI. Meanwhile, WTConv is embedded in the above modules to progressively mine the low-rank and sparse features of the DI in the frequency domain. Next, an iterative optimization scheme based on low-rank and sparse features is used to capture the change semantic details between Bi-HSIs. Finally, a wavelet convolution filter (WTCF) is designed and applied to the sparse components to reflect the image change information. Experiments on River and Farmland Bi-HSIs demonstrated that the proposed WISLNet method is able to achieve superior CD results compared with well-known and state-of-the-art deep networks.


## Results
Table I and Fig. 2 present the quantitative and qualitative change detection results of all the HSI-CD methods on the River and Farmland datasets, respectively. The proportion of labeled samples used for model training is 3%, and the rest are used as testing samples. It can be seen from Table I that the proposed WISLNet method achieves the highest accuracy on most performance metrics compared with the five competing methods on the River and Farmland datasets.

![Table](https://github.com/chengle-zhou/MY-IMAGE/blob/b6823005846f3440eb968b1f6096c2ee54dd9f69/WISLNet/img-2.jpg)

![Fig2](https://github.com/chengle-zhou/MY-IMAGE/blob/b6823005846f3440eb968b1f6096c2ee54dd9f69/WISLNet/img-3.jpg)

This section investigates the impact of three key hyperparameters (i.e., K, window size, and !t) on the change detection performance of the WISLNet on the River and Farmland datasets. As shown in Fig. 3(a), the detection performance of the WISLNet changes significantly with the value of K, and the performance of the WISLNet is optimal when K = 3.

![Fig3](https://github.com/chengle-zhou/MY-IMAGE/blob/b6823005846f3440eb968b1f6096c2ee54dd9f69/WISLNet/img-4.jpg)



In preparation for release soon.

Please cite our new paper:

**Plain Text:**

Chengle Zhou, Zhi He, Jian Dong, Yunfei Li, Jinchang Ren and Antonio Plaza, "[Wavelet-Inspired Sparse Learning Network for Hyperspectral Image Change Detection," in IEEE Geoscience and Remote Sensing Letters](https://ieeexplore.ieee.org/document/11003059)," ***IEEE Geoscience and Remote Sensing Letters***, vol. 22, pp. 1-5, 2025, Art no. 5505305, doi: 10.1109/LGRS.2025.3569718.

**BibTex:**

```latex
@article{Zhou2025WISLNet,
  title = {Wavelet-Inspired Sparse Learning Network for Hyperspectral Image Change Detection},
  volume = {22},
  ISSN = {1558-0571},
  url = {http://dx.doi.org/10.1109/LGRS.2025.3569718},
  DOI = {10.1109/lgrs.2025.3569718},
  journal = {IEEE Geoscience and Remote Sensing Letters},
  publisher = {Institute of Electrical and Electronics Engineers (IEEE)},
  author = {Zhou,  Chengle and He,  Zhi and Dong,  Jian and Zou,  Liwei},
  year = {2025},
  pages = {1–5}
}
```

