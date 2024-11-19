# MambaReg：基于 Mamba 的解缠卷积稀疏编码，用于无监督的可变形多模态图像配准

发布时间：2024年11月02日

`其他` `图像配准` `多模态图像`

> MambaReg: Mamba-Based Disentangled Convolutional Sparse Coding for Unsupervised Deformable Multi-Modal Image Registration

# 摘要

> 在具有固有特征差异的多模态图像精确对齐方面，可变形图像配准面临重大挑战。传统基于学习的方法常把配准网络视作不可解释的黑箱。核心观点是，跨模态分解对齐特征与非对齐特征是有益的。同时，像卷积神经网络这类用于图像配准任务的主流方法，因其局部感受野难以捕捉长距离依赖关系。当给定的图像对因缺乏有效学习长距离依赖和对应关系而存在较大不对齐时，这些方法往往失效。本文中，我们提出 MambaReg，这是一种新颖的基于 Mamba 的架构，整合了 Mamba 强大的长序列捕捉能力以应对这些挑战。通过我们提出的几个子模块，MambaReg 能有效区分负责配准的模态独立特征和模态相关的非对齐特征。通过有选择地关注相关特征，我们的网络能巧妙捕捉多模态图像间的相关性，实现精准的变形场预测和精确的图像对齐。基于 Mamba 的架构将卷积层的局部特征提取能力与 Mamba 的长距离依赖关系建模能力无缝融合。在公共非刚性 RGB-IR 图像数据集上的实验表明，我们的方法具有优越性，在配准精度和变形场平滑度方面优于现有方法。

> Precise alignment of multi-modal images with inherent feature discrepancies poses a pivotal challenge in deformable image registration. Traditional learning-based approaches often consider registration networks as black boxes without interpretability. One core insight is that disentangling alignment features and non-alignment features across modalities bring benefits. Meanwhile, it is challenging for the prominent methods for image registration tasks, such as convolutional neural networks, to capture long-range dependencies by their local receptive fields. The methods often fail when the given image pair has a large misalignment due to the lack of effectively learning long-range dependencies and correspondence. In this paper, we propose MambaReg, a novel Mamba-based architecture that integrates Mamba's strong capability in capturing long sequences to address these challenges. With our proposed several sub-modules, MambaReg can effectively disentangle modality-independent features responsible for registration from modality-dependent, non-aligning features. By selectively attending to the relevant features, our network adeptly captures the correlation between multi-modal images, enabling focused deformation field prediction and precise image alignment. The Mamba-based architecture seamlessly integrates the local feature extraction power of convolutional layers with the long-range dependency modeling capabilities of Mamba. Experiments on public non-rigid RGB-IR image datasets demonstrate the superiority of our method, outperforming existing approaches in terms of registration accuracy and deformation field smoothness.

[Arxiv](https://arxiv.org/abs/2411.01399)