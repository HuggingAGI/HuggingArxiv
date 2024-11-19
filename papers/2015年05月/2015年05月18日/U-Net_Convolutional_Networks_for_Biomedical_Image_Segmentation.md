# U-Net：应用于生物医学图像分割的卷积网络

发布时间：2015年05月18日

`其他` `图像识别`

> U-Net: Convolutional Networks for Biomedical Image Segmentation

# 摘要

> 摘要：大家普遍认同，深度网络若要训练成功，需要成千上万有标注的训练样本。在本文中，我们给出了一种网络及训练策略，其高度依赖数据增强，从而更高效地利用现有的有标注样本。该架构包含一条用于捕捉上下文的收缩路径，以及一条能实现精准定位的对称扩展路径。我们证明，这样的网络能够从极少的图像进行端到端训练，并且在电子显微镜堆栈中神经元结构分割的 ISBI 挑战里，表现优于此前的最佳方法（滑动窗口卷积网络）。运用在透射光显微镜图像（相差和 DIC）上训练的相同网络，我们在 2015 年 ISBI 细胞追踪挑战的相关类别中大幅领先。而且，该网络速度很快。在最新的 GPU 上，分割一张 512x512 的图像用时不到一秒。完整的实现（基于 Caffe）以及训练好的网络可通过此 http URL 获取。

> 
Abstract:There is large consent that successful training of deep networks requires many thousand annotated training samples. In this paper, we present a network and training strategy that relies on the strong use of data augmentation to use the available annotated samples more efficiently. The architecture consists of a contracting path to capture context and a symmetric expanding path that enables precise localization. We show that such a network can be trained end-to-end from very few images and outperforms the prior best method (a sliding-window convolutional network) on the ISBI challenge for segmentation of neuronal structures in electron microscopic stacks. Using the same network trained on transmitted light microscopy images (phase contrast and DIC) we won the ISBI cell tracking challenge 2015 in these categories by a large margin. Moreover, the network is fast. Segmentation of a 512x512 image takes less than a second on a recent GPU. The full implementation (based on Caffe) and the trained networks are available at this http URL .
    

[Arxiv](https://arxiv.org/pdf/1505.04597)