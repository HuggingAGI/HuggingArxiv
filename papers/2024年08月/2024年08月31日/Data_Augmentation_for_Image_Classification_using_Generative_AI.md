# 利用生成式AI技术，为图像分类任务进行数据增强

发布时间：2024年08月31日

`LLM应用` `计算机视觉` `人工智能`

> Data Augmentation for Image Classification using Generative AI

# 摘要

> 规模法则指出，AI模型的性能与数据量成正比。数据增强是扩展数据集的有效途径。传统方法通过旋转、平移和调整大小进行增强，而近期方法则利用生成式AI模型提升数据多样性。然而，生成方法在处理主题损坏和无关工件引入等问题上仍有挑战。本文提出自动化生成数据增强（AGA）框架，整合大型语言模型、扩散模型和分割模型，既保持前景真实性，又确保背景多样性。具体创新包括基于分段和超类的对象提取、通过提示分解实现组合复杂性的提示多样性，以及仿射主题操作。在ImageNet、CUB和iWildCam三个数据集上的实验表明，AGA相较于基线模型，在分布内和分布外数据上分别提升了15.6%和23.5%的准确性，SIC得分也提高了64.3%。

> Scaling laws dictate that the performance of AI models is proportional to the amount of available data. Data augmentation is a promising solution to expanding the dataset size. Traditional approaches focused on augmentation using rotation, translation, and resizing. Recent approaches use generative AI models to improve dataset diversity. However, the generative methods struggle with issues such as subject corruption and the introduction of irrelevant artifacts. In this paper, we propose the Automated Generative Data Augmentation (AGA). The framework combines the utility of large language models (LLMs), diffusion models, and segmentation models to augment data. AGA preserves foreground authenticity while ensuring background diversity. Specific contributions include: i) segment and superclass based object extraction, ii) prompt diversity with combinatorial complexity using prompt decomposition, and iii) affine subject manipulation. We evaluate AGA against state-of-the-art (SOTA) techniques on three representative datasets, ImageNet, CUB, and iWildCam. The experimental evaluation demonstrates an accuracy improvement of 15.6% and 23.5% for in and out-of-distribution data compared to baseline models, respectively. There is also a 64.3% improvement in SIC score compared to the baselines.

[Arxiv](https://arxiv.org/abs/2409.00547)