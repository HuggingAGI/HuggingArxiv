# VLTP：面向任务分割的视觉-语言引导令牌剪枝

发布时间：2024年09月12日

`LLM应用` `计算机视觉`

> VLTP: Vision-Language Guided Token Pruning for Task-Oriented Segmentation

# 摘要

> Vision Transformers (ViTs) 作为许多分割模型的核心，持续刷新性能纪录。然而，其高计算成本也令人头疼。图像令牌剪枝虽是解决之道，但在复杂的任务导向分割 (TOS) 中，效果有限，因为图像块的类别并非预设，而是随任务变化。为此，我们推出了视觉语言引导的令牌剪枝 (VLTP)，专为多模态大型语言模型 (MLLM) 引导的 TOS 设计，旨在加速 ViT 模型。我们坚信，ViT 无需处理所有令牌，只需关注与任务相关的部分。通过新设计的剪枝解码器，结合图像令牌与视觉语言指导，精准筛选出高相关令牌，送入 ViT 深层。实验结果亮眼：VLTP 在不损性能的前提下，将计算成本削减了 25%，甚至在性能仅微降 1% 的情况下，成本降低了 40%。

> Vision Transformers (ViTs) have emerged as the backbone of many segmentation models, consistently achieving state-of-the-art (SOTA) performance. However, their success comes at a significant computational cost. Image token pruning is one of the most effective strategies to address this complexity. However, previous approaches fall short when applied to more complex task-oriented segmentation (TOS), where the class of each image patch is not predefined but dependent on the specific input task. This work introduces the Vision Language Guided Token Pruning (VLTP), a novel token pruning mechanism that can accelerate ViTbased segmentation models, particularly for TOS guided by multi-modal large language model (MLLM). We argue that ViT does not need to process every image token through all of its layers only the tokens related to reasoning tasks are necessary. We design a new pruning decoder to take both image tokens and vision-language guidance as input to predict the relevance of each image token to the task. Only image tokens with high relevance are passed to deeper layers of the ViT. Experiments show that the VLTP framework reduces the computational costs of ViT by approximately 25% without performance degradation and by around 40% with only a 1% performance drop.

[Arxiv](https://arxiv.org/abs/2409.08464)