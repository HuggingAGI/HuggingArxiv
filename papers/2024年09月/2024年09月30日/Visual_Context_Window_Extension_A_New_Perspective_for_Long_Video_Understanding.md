# 视觉上下文窗口扩展：探索长视频理解的新途径

发布时间：2024年09月30日

`LLM应用` `视频处理` `人工智能`

> Visual Context Window Extension: A New Perspective for Long Video Understanding

# 摘要

> 大型多模态模型（LMMs）在短视频理解中表现优异，但在长视频理解上却遇到瓶颈。相反，大型语言模型（LLMs）在处理长文本时表现卓越。现有研究尝试通过引入长视频-文本对来解决这一问题，但需要大量计算和数据资源。本文从上下文窗口的角度出发，探讨如何在不重新训练长视频数据集的情况下，将LMMs应用于长视频任务。我们首先分析了预训练LMMs在长视频理解上的困难，发现视觉与语言模态间的差异导致上下文窗口不一致，难以直接扩展视觉标记。为此，我们提出扩展视觉上下文窗口的方法，无需重新训练。此外，为减少长序列带来的内存压力，我们设计了渐进池化推理策略，通过调整帧嵌入的空间分辨率，减少视觉标记数量并保留关键信息。实验结果显示，随着视频帧数增加，我们的方法在多个长视频理解基准测试中表现持续提升。在MLVU基准测试中，尽管模型规模仅为7B，我们的方法仍超越了GPT-4o。同时，在256帧设置下，我们的方法将内存使用量降低了约45%，且未损失性能。

> Large Multimodal Models (LMMs) have demonstrated impressive performance in short video understanding tasks but face great challenges when applied to long video understanding. In contrast, Large Language Models (LLMs) exhibit outstanding capabilities in modeling long texts. Existing work attempts to address this issue by introducing long video-text pairs during training. However, these approaches require substantial computational and data resources. In this paper, we tackle the challenge of long video understanding from the perspective of context windows, aiming to apply LMMs to long video tasks without retraining on long video datasets. We first conduct an in-depth analysis of why pretrained LMMs struggle to understand lengthy video content, identifying that discrepancies between visual and language modalities lead to different context windows for visual and language tokens, making it difficult to directly extend the visual tokens to match the language context window. Based on this, we propose to adapt LMMs for long video understanding tasks by extending the visual context window, eliminating the need for retraining on large scalelong video datasets. To further mitigate the significant memory consumption caused by long sequences, we introduce a progressive pooling inference strategy that selectively adjusts the spatial resolution of frame embeddings, reducing the number of visual tokens while retaining important spatial information. Across multiple long video understanding benchmarks, our method consistently improves the performance as the number of video frames increases. On the MLVU benchmark, our method outperforms GPT-4o, even though our model size is only 7B. Additionally, in the 256-frame setting, our method reduces memory usage by approximately 45% compared to the baseline, without introducing any performance loss.

[Arxiv](https://arxiv.org/abs/2409.20018)