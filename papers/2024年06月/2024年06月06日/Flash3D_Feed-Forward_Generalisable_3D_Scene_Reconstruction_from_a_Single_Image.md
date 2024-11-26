# Flash3D：实现从单张图像进行前馈式可泛化的 3D 场景重建

发布时间：2024年06月06日

`其他` `计算机视觉` `3D 重建`

> Flash3D: Feed-Forward Generalisable 3D Scene Reconstruction from a Single Image

# 摘要

> 摘要：在本文中，我们推出了 Flash3D，这是一种能从单张图像进行场景重建和新视角合成的方法，它通用性强且效率高。为达通用性，我们以单目深度估计的“基础”模型为起点，将其拓展为完整的 3D 形状和外观重建器。为求高效，我们基于前馈高斯喷溅来做此拓展。具体来说，我们先在预测的深度处预测第一层 3D 高斯，接着添加在空间上有偏移的额外高斯层，让模型能够完成遮挡和截断后的重建。Flash3D 效率极高，一天内就能在单个 GPU 上完成训练，所以多数研究人员都能使用。在 RealEstate10k 上训练和测试时，它取得了顶尖成果。转移到像 NYU 这样未曾见过的数据集时，它大幅领先竞争对手。更令人惊叹的是，转移到 KITTI 时，Flash3D 实现的 PSNR 比专门在该数据集上训练的方法还好。在某些情况下，它甚至比使用多个视图作为输入的最新方法更出色。代码、模型、演示及更多结果可在这个 https URL 获取。

> 
Abstract:In this paper, we propose Flash3D, a method for scene reconstruction and novel view synthesis from a single image which is both very generalisable and efficient. For generalisability, we start from a "foundation" model for monocular depth estimation and extend it to a full 3D shape and appearance reconstructor. For efficiency, we base this extension on feed-forward Gaussian Splatting. Specifically, we predict a first layer of 3D Gaussians at the predicted depth, and then add additional layers of Gaussians that are offset in space, allowing the model to complete the reconstruction behind occlusions and truncations. Flash3D is very efficient, trainable on a single GPU in a day, and thus accessible to most researchers. It achieves state-of-the-art results when trained and tested on RealEstate10k. When transferred to unseen datasets like NYU it outperforms competitors by a large margin. More impressively, when transferred to KITTI, Flash3D achieves better PSNR than methods trained specifically on that dataset. In some instances, it even outperforms recent methods that use multiple views as input. Code, models, demo, and more results are available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2406.04343)