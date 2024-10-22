# 模态公平偏好优化，助力多模态语言模型的可信对齐

发布时间：2024年10月20日

`LLM应用` `人工智能` `计算机视觉`

> Modality-Fair Preference Optimization for Trustworthy MLLM Alignment

# 摘要

> 直接偏好优化 (DPO) 在调整大型语言模型 (LLM) 方面表现出色，但应用于多模态模型 (MLLM) 时，常偏向文本而忽视图像，导致输出不可靠和视觉幻觉。为此，我们提出模态公平偏好优化 (MFPO)，旨在平衡文本与图像的偏好。首先，我们发现偏好数据中缺乏图像奖励，导致优化偏向文本，因此我们生成了自动化、细粒度的图像偏好数据来纠正这一偏差。接着，我们设计了一个学习目标，确保模型既能捕捉文本偏好，也能捕捉图像偏好，同时保持输出质量。最后，我们采用多阶段对齐方法，稳定训练过程，提升两种模态的学习效果。实验结果显示，MFPO 显著提升了 MLLM 的可信度。在 LLaVA-v1.5 (7B, 13B) 等模型上，MFPO 大幅减少了幻觉现象。在 7B 模型上，MFPO 超越了 GPT-4V，在 Object HalBench 上比之前的方法提升了近 40%，并在结合最新 LLaVA-v1.6 时，在 Object HalBench 和 AMBER 上达到了业界领先水平。代码即将发布。

> Direct Preference Optimization (DPO) is effective for aligning large language models (LLMs), but when applied to multimodal models (MLLMs), it often favors text over image information, leading to unreliable outputs and visual hallucinations. To address this, we propose Modality-Fair Preference Optimization (MFPO) to balance text and image preferences. First, we found that the lack of image-related rewards in preference data biases optimization toward text, so we created automated, fine-grained image preference data to correct this. Then, we designed a learning objective to ensure the model captures both text and image preferences while maintaining high-quality outputs. Finally, we use a multi-stage alignment approach to stabilize training and improve learning across both modalities. Extensive experiments demonstrate that MFPO significantly enhances MLLM trustworthiness. On models like LLaVA-v1.5 (7B, 13B), our approach reduces hallucinations substantially. On the 7B model, MFPO outperforms GPT-4V and achieves a nearly 40\% improvement over previous methods on Object HalBench, as well as achieving state-of-the-art performance on both Object HalBench and AMBER when combined with the latest LLaVA-v1.6. Code will be released.

[Arxiv](https://arxiv.org/abs/2410.15334)