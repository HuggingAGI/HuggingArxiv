# CoVLM：借助视觉-语言模型的共识，实现半监督多模态假新闻检测

发布时间：2024年10月06日

`LLM应用` `信息安全`

> CoVLM: Leveraging Consensus from Vision-Language Models for Semi-supervised Multi-modal Fake News Detection

# 摘要

> 我们针对现实世界中的一项艰巨任务——上下文外错误信息检测，即通过将真实图像与错误标题配对来制造假新闻。现有方法依赖大量标记数据，这在实际操作中往往难以实现，因为需要大量人工干预和专业知识。相反，获取未标记的图像-文本对则相对容易。因此，我们提出了一种半监督方法，模型可利用少量标记数据和大量未标记数据。此外，假新闻数量远少于真实新闻，导致数据集极度不平衡，任务难度倍增。为此，我们创新性地提出了视觉语言模型共识框架（CoVLM），利用标记数据生成的阈值为未标记数据生成可靠的伪标签，自动调整模型参数以筛选出可信的伪标签。实验结果表明，在各种挑战性条件下，我们的框架均表现出色，优于当前最先进的方法。

> In this work, we address the real-world, challenging task of out-of-context misinformation detection, where a real image is paired with an incorrect caption for creating fake news. Existing approaches for this task assume the availability of large amounts of labeled data, which is often impractical in real-world, since it requires extensive manual intervention and domain expertise. In contrast, since obtaining a large corpus of unlabeled image-text pairs is much easier, here, we propose a semi-supervised protocol, where the model has access to a limited number of labeled image-text pairs and a large corpus of unlabeled pairs. Additionally, the occurrence of fake news being much lesser compared to the real ones, the datasets tend to be highly imbalanced, thus making the task even more challenging. Towards this goal, we propose a novel framework, Consensus from Vision-Language Models (CoVLM), which generates robust pseudo-labels for unlabeled pairs using thresholds derived from the labeled data. This approach can automatically determine the right threshold parameters of the model for selecting the confident pseudo-labels. Experimental results on benchmark datasets across challenging conditions and comparisons with state-of-the-art approaches demonstrate the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2410.04426)