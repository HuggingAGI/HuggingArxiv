# 借助大型多模态模型进行比较学习，实现图像质量的自适应评估

发布时间：2024年05月29日

`LLM应用

这篇论文介绍了一种基于大型多模态模型（LMM）的无参考图像质量评估（IQA）模型，名为Compare2Score。该模型能够将离散的图像质量比较结果转化为连续的质量评分，这在图像质量评估领域是一个重要的应用。论文中提到的技术细节和实验结果表明，该模型在多个IQA数据集上表现出色，并且通过概率矩阵的推理方法提升了模型的准确性和通用性。因此，这篇论文属于LLM应用分类，因为它展示了大型多模态模型在特定应用领域（图像质量评估）的具体应用和效果。` `图像质量评估` `多模态模型`

> Adaptive Image Quality Assessment via Teaching Large Multimodal Model to Compare

# 摘要

> 尽管大型多模态模型在图像质量评估方面取得了显著进步，但如何将相对质量比较结果转化为连续感知质量分数仍是一个未解之谜。为此，我们推出了Compare2Score，这是一种基于LMM的无参考IQA模型，能够进行定性比较并巧妙地将离散比较结果转化为连续质量评分。在训练中，我们通过比较同一数据集中的图像来生成详细的比较指令，使得模型能灵活适应不同的IQA数据集。借助庞大的训练数据，我们构建了一个类似人类的视觉质量比较器。在推理时，我们采用了一种软比较策略，计算测试图像相对于多个锚定图像的偏好概率，并通过最大后验估计优化质量分数。实验证明，Compare2Score在多个IQA数据集上表现卓越，有效连接了训练中的文本比较与推理中的单图像质量评分，超越了现有技术。此外，这种基于概率矩阵的推理方法不仅提升了Compare2Score的准确性，还增强了零-shot通用LMMs的性能，展现了其内在的有效性。

> While recent advancements in large multimodal models (LMMs) have significantly improved their abilities in image quality assessment (IQA) relying on absolute quality rating, how to transfer reliable relative quality comparison outputs to continuous perceptual quality scores remains largely unexplored. To address this gap, we introduce Compare2Score-an all-around LMM-based no-reference IQA (NR-IQA) model, which is capable of producing qualitatively comparative responses and effectively translating these discrete comparative levels into a continuous quality score. Specifically, during training, we present to generate scaled-up comparative instructions by comparing images from the same IQA dataset, allowing for more flexible integration of diverse IQA datasets. Utilizing the established large-scale training corpus, we develop a human-like visual quality comparator. During inference, moving beyond binary choices, we propose a soft comparison method that calculates the likelihood of the test image being preferred over multiple predefined anchor images. The quality score is further optimized by maximum a posteriori estimation with the resulting probability matrix. Extensive experiments on nine IQA datasets validate that the Compare2Score effectively bridges text-defined comparative levels during training with converted single image quality score for inference, surpassing state-of-the-art IQA models across diverse scenarios. Moreover, we verify that the probability-matrix-based inference conversion not only improves the rating accuracy of Compare2Score but also zero-shot general-purpose LMMs, suggesting its intrinsic effectiveness.

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/x1.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/x2.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/x3.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/x4.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/80184044.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/396505725.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/5050399849.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/5261188573.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/5993929800.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/I58_04_05.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/I61_15_04.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/I64_12_04.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/I80_11_02.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/I30_19_01.png)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/AttnGAN_normal_293.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/AttnGAN_normal_193.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/sd1.5_highcorr_176.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/midjourney_lowstep_186.jpg)

![借助大型多模态模型进行比较学习，实现图像质量的自适应评估](../../../paper_images/2405.19298/midjourney_normal_086.jpg)

[Arxiv](https://arxiv.org/abs/2405.19298)