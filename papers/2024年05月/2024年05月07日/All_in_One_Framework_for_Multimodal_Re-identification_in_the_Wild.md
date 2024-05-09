# 一体式框架：野外多模态身份再识别的全面解决方案

发布时间：2024年05月07日

`Agent

这篇论文介绍了一种名为“一体式”（AIO）的多模态学习范式，它利用预训练的大型模型作为编码器来实现多模态检索。这种范式可以被视为一个智能代理（Agent），因为它能够处理和整合多种类型的数据，并在不同的场景中执行检索任务。AIO框架的设计和实现展示了如何构建一个能够跨模态工作的智能系统，这与Agent的概念相符，即一个能够感知环境、做出决策并执行动作的系统。因此，这篇论文更适合归类到Agent分类中。` `多模态学习` `图像检索`

> All in One Framework for Multimodal Re-identification in the Wild

# 摘要

> 在ReID领域，尽管单模态和跨模态检索技术取得了显著进展，但构建一个能有效整合多种数据（如RGB、红外、草图和文本）的统一框架仍是一大挑战。同时，虽然大型模型在视觉任务中表现出色，但ReID的基础模型尚未成型。为此，我们提出了“一体式”（AIO）多模态学习范式，它采用预训练的大型模型作为编码器，无需微调即可实现高效的多模态检索。AIO将多样的数据统一标记化，使得共享编码器能够跨模态提取一致的身份特征。我们还精心设计了跨模态头部，以引导学习过程。作为首个实现一体式ReID的框架，AIO涵盖了四种常见模态，并在实验中证明了其在处理复杂模态数据和在零-shot及领域泛化场景中的卓越性能。

> In Re-identification (ReID), recent advancements yield noteworthy progress in both unimodal and cross-modal retrieval tasks. However, the challenge persists in developing a unified framework that could effectively handle varying multimodal data, including RGB, infrared, sketches, and textual information. Additionally, the emergence of large-scale models shows promising performance in various vision tasks but the foundation model in ReID is still blank. In response to these challenges, a novel multimodal learning paradigm for ReID is introduced, referred to as All-in-One (AIO), which harnesses a frozen pre-trained big model as an encoder, enabling effective multimodal retrieval without additional fine-tuning. The diverse multimodal data in AIO are seamlessly tokenized into a unified space, allowing the modality-shared frozen encoder to extract identity-consistent features comprehensively across all modalities. Furthermore, a meticulously crafted ensemble of cross-modality heads is designed to guide the learning trajectory. AIO is the \textbf{first} framework to perform all-in-one ReID, encompassing four commonly used modalities. Experiments on cross-modal and multimodal ReID reveal that AIO not only adeptly handles various modal data but also excels in challenging contexts, showcasing exceptional performance in zero-shot and domain generalization scenarios.

[Arxiv](https://arxiv.org/abs/2405.04741)