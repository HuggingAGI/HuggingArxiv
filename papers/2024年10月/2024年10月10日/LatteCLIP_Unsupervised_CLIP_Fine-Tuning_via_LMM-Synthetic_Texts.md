# LatteCLIP：利用 LMM 生成的合成文本，实现无监督的 CLIP 微调

发布时间：2024年10月10日

`LLM应用` `计算机视觉` `人工智能`

> LatteCLIP: Unsupervised CLIP Fine-Tuning via LMM-Synthetic Texts

# 摘要

> CLIP 等大规模视觉-语言预训练模型在零-shot 应用中表现出色，但一旦涉及特定领域，性能往往因领域差异或训练数据不足而受限。虽然通过人工标注数据集进行微调可以改善这一问题，但标注成本高昂，尤其在任务复杂时。为此，我们推出了 LatteCLIP，一种无需人工标注即可在自定义领域微调 CLIP 的无监督方法。该方法借助大型多模态模型生成详尽的图像描述，为微调提供额外上下文。针对描述可能存在的失真问题，我们设计了信息提纯与训练稳定策略。实验结果显示，LatteCLIP 在多个领域数据集上，平均准确率显著提升，分别超越零-shot 方法 4.74 分和现有无监督方法 3.45 分。

> Large-scale vision-language pre-trained (VLP) models (e.g., CLIP) are renowned for their versatility, as they can be applied to diverse applications in a zero-shot setup. However, when these models are used in specific domains, their performance often falls short due to domain gaps or the under-representation of these domains in the training data. While fine-tuning VLP models on custom datasets with human-annotated labels can address this issue, annotating even a small-scale dataset (e.g., 100k samples) can be an expensive endeavor, often requiring expert annotators if the task is complex. To address these challenges, we propose LatteCLIP, an unsupervised method for fine-tuning CLIP models on classification with known class names in custom domains, without relying on human annotations. Our method leverages Large Multimodal Models (LMMs) to generate expressive textual descriptions for both individual images and groups of images. These provide additional contextual information to guide the fine-tuning process in the custom domains. Since LMM-generated descriptions are prone to hallucination or missing details, we introduce a novel strategy to distill only the useful information and stabilize the training. Specifically, we learn rich per-class prototype representations from noisy generated texts and dual pseudo-labels. Our experiments on 10 domain-specific datasets show that LatteCLIP outperforms pre-trained zero-shot methods by an average improvement of +4.74 points in top-1 accuracy and other state-of-the-art unsupervised methods by +3.45 points.

[Arxiv](https://arxiv.org/abs/2410.08211)