# Neural Feature Engineering

This repo collects implementations of **feature geometry**, a mathematical framework designed for principled representation learning with deep neural networks as building blocks.

![Fig1](https://github.com/XiangxiangXu/NFE/blob/main/fig1.png)

## [Neural Feature Learning in Function Space](https://arxiv.org/pdf/2309.10140.pdf)

### Learning Modal Decomposition 
Hirschfeld-Gebelein-Rényi (HGR) maximal correlation functions
- [Nested_H_Score](https://github.com/XiangxiangXu/NFE/blob/main/Nested_H_Score.ipynb)
- [H_score_Seq](https://github.com/XiangxiangXu/NFE/blob/main/H_score_Seq.ipynb)
- [MaxCorr_Normal](https://github.com/XiangxiangXu/NFE/blob/main/MaxCorr_Normal.ipynb): compute maximal correlation functions for normal variables

### Learning With Orthogonality Constraints
Learn features uncorrelated with given features
- [f_orth_cosine](https://github.com/XiangxiangXu/NFE/blob/main/f_orth_cosine.ipynb)

### Learning With Side Information (Conditioned Inference)
- [SideInfo_multihead](https://github.com/XiangxiangXu/NFE/blob/main/SideInfo_multihead.ipynb)
  
### Multimodal Learning With Missing Modalities
- [mm_cosine](https://github.com/XiangxiangXu/NFE/blob/main/mm_cosine.ipynb)
- [mm_pair_cosine](https://github.com/XiangxiangXu/NFE/blob/main/mm_pair_cosine.ipynb)


## [Sequential Dependence Decomposition and Feature Learning](https://ieeexplore.ieee.org/document/10313384) 
### Sequential Dependence Decomposition 
- [SEQ](https://github.com/XiangxiangXu/NFE/blob/main/SEQ.ipynb): decomposing sequential dependence into Markov chains of different orders.

# References 
[1] Xu, Xiangxiang, and Shao-Lun Huang. "Maximal correlation regression." IEEE Access 8 (2020): 26591-26601.

[2] Xu, Xiangxiang, and Lizhong Zheng. "Sequential Dependence Decomposition and Feature Learning." 2023 59th Annual Allerton Conference on Communication, Control, and Computing (Allerton). IEEE, 2023.

[3] Xu, Xiangxiang, and Lizhong Zheng. "Neural Feature Learning in Function Space." arXiv preprint arXiv:2309.10140 (2024).
