# 学习在何处编辑视觉转换器

发布时间：2024年11月04日

`其他` `计算机视觉` `模型编辑`

> Learning Where to Edit Vision Transformers

# 摘要

> 模型编辑旨在以数据高效的方式纠正大型预训练模型的预测错误，同时确保对相邻故障的泛化能力和局部性，以最大程度减少对不相关示例的意外影响。虽然在编辑基于 Transformer 的大型语言模型方面取得了显著进展，但在计算机视觉中编辑视觉 Transformer（ViTs）的有效策略在很大程度上仍未得到开发。在本文中，我们朝着纠正 ViTs 的预测错误迈出了初步的步伐，特别是那些由子群体转移引起的错误。采用先定位后编辑的方法，我们首先通过在为编辑可靠性生成的 CutMix 增强数据上元学习一个超网络来解决在哪里编辑的挑战。这个经过训练的超网络产生了可推广的二值掩码，用于识别结构化模型参数的稀疏子集，对现实世界的故障样本做出响应。之后，我们通过使用梯度下降的变体简单地微调所识别的参数来解决如何编辑的问题，以实现成功的编辑。为了验证我们的方法，我们构建了一个编辑基准，将子群体转移引入到自然的代表性不足的图像和 AI 生成的图像中，从而揭示了预训练 ViTs 在对象识别方面的局限性。我们的方法不仅在提出的基准上取得了优越的性能，而且还允许在泛化和局部性之间进行可调节的权衡。我们的代码可在 https://github.com/hustyyq/Where-to-Edit 获得。

> Model editing aims to data-efficiently correct predictive errors of large pre-trained models while ensuring generalization to neighboring failures and locality to minimize unintended effects on unrelated examples. While significant progress has been made in editing Transformer-based large language models, effective strategies for editing vision Transformers (ViTs) in computer vision remain largely untapped. In this paper, we take initial steps towards correcting predictive errors of ViTs, particularly those arising from subpopulation shifts. Taking a locate-then-edit approach, we first address the where-to-edit challenge by meta-learning a hypernetwork on CutMix-augmented data generated for editing reliability. This trained hypernetwork produces generalizable binary masks that identify a sparse subset of structured model parameters, responsive to real-world failure samples. Afterward, we solve the how-to-edit problem by simply fine-tuning the identified parameters using a variant of gradient descent to achieve successful edits. To validate our method, we construct an editing benchmark that introduces subpopulation shifts towards natural underrepresented images and AI-generated images, thereby revealing the limitations of pre-trained ViTs for object recognition. Our approach not only achieves superior performance on the proposed benchmark but also allows for adjustable trade-offs between generalization and locality. Our code is available at https://github.com/hustyyq/Where-to-Edit.

[Arxiv](https://arxiv.org/abs/2411.01948)