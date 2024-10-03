# 小数据集上的文本到图像生成中的数据外推

发布时间：2024年10月02日

`LLM应用` `计算机视觉` `图像生成`

> Data Extrapolation for Text-to-image Generation on Small Datasets

# 摘要

> 文本到图像生成需要大量训练数据来合成高质量图像。传统方法通过裁剪、翻转等数据插值手段增强训练数据，但这些方法无法引入新信息，改进有限。本文提出一种新方法，通过线性外推文本特征，并利用搜索引擎从互联网检索新图像数据，实现数据增强。为确保新文本-图像对的可靠性，我们设计了两个异常检测器净化检索图像。基于外推，我们构建的训练样本比原始数据集大几十倍，显著提升文本到图像生成性能。此外，我们提出NULL-guidance优化评分估计，并应用循环仿射变换融合文本信息。模型在CUB、Oxford和COCO数据集上分别取得7.91、9.52和5.00的FID分数。代码和数据将在GitHub上发布（https://github.com/senmaoy/RAT-Diffusion）。

> Text-to-image generation requires large amount of training data to synthesizing high-quality images. For augmenting training data, previous methods rely on data interpolations like cropping, flipping, and mixing up, which fail to introduce new information and yield only marginal improvements. In this paper, we propose a new data augmentation method for text-to-image generation using linear extrapolation. Specifically, we apply linear extrapolation only on text feature, and new image data are retrieved from the internet by search engines. For the reliability of new text-image pairs, we design two outlier detectors to purify retrieved images. Based on extrapolation, we construct training samples dozens of times larger than the original dataset, resulting in a significant improvement in text-to-image performance. Moreover, we propose a NULL-guidance to refine score estimation, and apply recurrent affine transformation to fuse text information. Our model achieves FID scores of 7.91, 9.52 and 5.00 on the CUB, Oxford and COCO datasets. The code and data will be available on GitHub (https://github.com/senmaoy/RAT-Diffusion).

[Arxiv](https://arxiv.org/abs/2410.01638)