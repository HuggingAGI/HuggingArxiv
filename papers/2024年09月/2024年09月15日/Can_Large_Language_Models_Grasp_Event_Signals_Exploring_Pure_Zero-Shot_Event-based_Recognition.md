# 大型语言模型能否捕捉事件信号？探索纯零-shot 事件识别的可能性

发布时间：2024年09月15日

`LLM应用` `计算机视觉` `人工智能`

> Can Large Language Models Grasp Event Signals? Exploring Pure Zero-Shot Event-based Recognition

# 摘要

> 近期，基于事件的零-shot 物体识别技术取得了显著进展，但这些方法依赖大量训练，且受限于 CLIP 的特性。本研究首次探索了大型语言模型 (LLM) 对基于事件视觉内容的理解能力。我们发现，LLM 无需额外训练或微调，结合 CLIP 即可实现基于事件的物体识别，从而实现纯粹的零-shot 识别。我们特别评估了 GPT-4o / 4turbo 及其他两个开源 LLM 的识别能力。通过在三个基准数据集上的广泛实验，我们系统评估了这些模型的识别准确性。结果表明，经过精心设计的提示增强后，LLM 显著提升了基于事件的零-shot 识别性能。尤其值得一提的是，GPT-4o 在 N-ImageNet 上的识别准确性超越了现有最先进方法五个数量级。本文的实现代码已公开，详见 \url{https://github.com/ChrisYu-Zz/Pure-event-based-recognition-based-LLM}。

> Recent advancements in event-based zero-shot object recognition have demonstrated promising results. However, these methods heavily depend on extensive training and are inherently constrained by the characteristics of CLIP. To the best of our knowledge, this research is the first study to explore the understanding capabilities of large language models (LLMs) for event-based visual content. We demonstrate that LLMs can achieve event-based object recognition without additional training or fine-tuning in conjunction with CLIP, effectively enabling pure zero-shot event-based recognition. Particularly, we evaluate the ability of GPT-4o / 4turbo and two other open-source LLMs to directly recognize event-based visual content. Extensive experiments are conducted across three benchmark datasets, systematically assessing the recognition accuracy of these models. The results show that LLMs, especially when enhanced with well-designed prompts, significantly improve event-based zero-shot recognition performance. Notably, GPT-4o outperforms the compared models and exceeds the recognition accuracy of state-of-the-art event-based zero-shot methods on N-ImageNet by five orders of magnitude. The implementation of this paper is available at \url{https://github.com/ChrisYu-Zz/Pure-event-based-recognition-based-LLM}.

[Arxiv](https://arxiv.org/abs/2409.09628)