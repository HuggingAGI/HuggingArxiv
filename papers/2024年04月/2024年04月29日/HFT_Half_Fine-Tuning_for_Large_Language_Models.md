# HFT：为大型语言模型量身定制的半微调技术

发布时间：2024年04月29日

`LLM理论` `机器学习`

> HFT: Half Fine-Tuning for Large Language Models

# 摘要

> 大型语言模型（LLMs）通过一个或多个微调阶段，已成为实现多样化功能的关键步骤，让模型能够遵循自然语言指令或适应人类的偏好。但这种顺序训练可能会引发灾难性遗忘，即早期学习的知识或能力可能被新的训练数据所覆盖。本文研究发现，定期重置部分参数有助于模型恢复一些原有知识。基于这一发现，我们提出了一种新的半微调（Half Fine-Tuning，HFT）方法，作为完全微调（Full Fine-Tuning，FFT）的替代方案，以缓解遗忘问题。在这种方法中，一半的参数用于学习新任务，而另一半则保持不变以维持之前的知识。我们从优化的角度对HFT进行了可行性分析，并将参数选择视为一种正则化手段。HFT可以无缝地融入现有的微调流程，而无需改变模型架构。通过在监督微调、直接偏好优化和持续学习等多个方面的广泛实验和分析，HFT展现了其在有效性、鲁棒性和效率上的优势。相较于FFT，HFT显著减少了遗忘问题，同时在多个下游任务基准测试中取得了最佳性能，并大幅缩短了约30%的训练时间。

> Large language models (LLMs) with one or more fine-tuning phases have become a necessary step to unlock various capabilities, enabling LLMs to follow natural language instructions or align with human preferences. However, it carries the risk of catastrophic forgetting during sequential training, the parametric knowledge or the ability learned in previous stages may be overwhelmed by incoming training data. In this paper, we find that by regularly resetting partial parameters, LLMs can restore some of the original knowledge. Inspired by this, we introduce Half Fine-Tuning (HFT) for LLMs, as a substitute for full fine-tuning (FFT), to mitigate the forgetting issues, where half of the parameters are selected to learn new tasks while the other half are frozen to remain previous knowledge. We provide a feasibility analysis from the perspective of optimization and interpret the parameter selection operation as a regularization term. Without changing the model architecture, HFT could be seamlessly integrated into existing fine-tuning frameworks. Extensive experiments and analysis on supervised fine-tuning, direct preference optimization, and continual learning consistently demonstrate the effectiveness, robustness, and efficiency of HFT. Compared with FFT, HFT not only significantly alleviates the forgetting problem, but also achieves the best performance in a series of downstream benchmarks, with an approximately 30% reduction in training time.

[Arxiv](https://arxiv.org/abs/2404.18466)