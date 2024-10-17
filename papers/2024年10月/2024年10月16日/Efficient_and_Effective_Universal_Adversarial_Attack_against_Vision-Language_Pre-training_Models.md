# 针对视觉-语言预训练模型，我们提出了一种既高效又有效的通用对抗攻击方法。

发布时间：2024年10月16日

`其他` `计算机视觉` `人工智能安全`

> Efficient and Effective Universal Adversarial Attack against Vision-Language Pre-training Models

# 摘要

> 视觉-语言预训练模型（VLP）在处理视觉与语言任务时表现出色，但其广泛应用也使其易受对抗攻击。传统的非通用对抗攻击虽有效，但计算成本高，不适用于实时应用。为此，我们提出了基于直接优化的通用对抗扰动方法（DO-UAP），不仅大幅降低资源消耗，还保持了高攻击性能。通过深入研究多模态损失设计及数据增强策略，我们在多个基准数据集和模型上验证了DO-UAP的高效与有效性。实验结果显示，DO-UAP将时间消耗减少了23倍，攻击效果更佳。

> Vision-language pre-training (VLP) models, trained on large-scale image-text pairs, have become widely used across a variety of downstream vision-and-language (V+L) tasks. This widespread adoption raises concerns about their vulnerability to adversarial attacks. Non-universal adversarial attacks, while effective, are often impractical for real-time online applications due to their high computational demands per data instance. Recently, universal adversarial perturbations (UAPs) have been introduced as a solution, but existing generator-based UAP methods are significantly time-consuming. To overcome the limitation, we propose a direct optimization-based UAP approach, termed DO-UAP, which significantly reduces resource consumption while maintaining high attack performance. Specifically, we explore the necessity of multimodal loss design and introduce a useful data augmentation strategy. Extensive experiments conducted on three benchmark VLP datasets, six popular VLP models, and three classical downstream tasks demonstrate the efficiency and effectiveness of DO-UAP. Specifically, our approach drastically decreases the time consumption by 23-fold while achieving a better attack performance.

[Arxiv](https://arxiv.org/abs/2410.11639)