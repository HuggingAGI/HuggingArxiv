# DESTEIN：利用通用指令对和逐步激活整合技术引导语言模型净化之旅

发布时间：2024年04月16日

`LLM应用` `内容净化` `语言模型`

> DESTEIN: Navigating Detoxification of Language Models via Universal Steering Pairs and Head-wise Activation Fusion

# 摘要

> 语言模型（LMs）在众多任务中取得了卓越成就，但其产生有害内容的风险也备受关注。现有解决方案，如微调和辅助模型，往往需要巨大的内存和计算资源，对于大型语言模型（LLMs）的实际应用并不切实际。本文提出了一种创新的DeStein方法，通过在激活空间内调整内部表示，以较低的资源和时间消耗为LMs解毒。我们运用自我引导配对策略，在激活空间中通过算术运算确定解毒向量。在推理阶段，将解毒向量与原始表示结合，实现内容净化。实验结果显示，该方法在常见解毒评价指标上超越了先前的技术，同时保持了生成内容的质量和多样性。此外，我们还验证了该方法在多个LLMs上的实用性和扩展性。注意：部分示例输出可能包含极具攻击性或不适的内容。

> Despite the remarkable achievements of language models (LMs) across a broad spectrum of tasks, their propensity for generating toxic outputs remains a prevalent concern. Current solutions involving fine-tuning or auxiliary models usually require extensive memory and computational resources, rendering them less practical for deployment in large language models (LLMs). In this paper, we propose DeStein, a novel method that detoxififies LMs by altering their internal representations in the activation space with lower resource and time cost. Specifically, we leverage self-induced steering pairs to identify detoxification vectors through arithmetic operations in the activation space. During inference, detoxification is achieved by blending the detoxification vectors with the original representations. Empirical results demonstrate that our method significantly outperforms previous state-of-the-art approaches on popular detoxification metrics, while also maintaining satisfactory generation quality and diversity. Furthermore, we extend our method to multiple LLMs, demonstrating its practicality and scalability. Warning: some example model outputs contain highly offensive or disturbing text.

[Arxiv](https://arxiv.org/abs/2404.10464)