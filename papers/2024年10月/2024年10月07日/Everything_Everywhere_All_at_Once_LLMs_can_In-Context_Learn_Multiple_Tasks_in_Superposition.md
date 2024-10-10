# LLM 能够瞬间掌握多任务，一切尽在超位置中的上下文学习。

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Everything Everywhere All at Once: LLMs can In-Context Learn Multiple Tasks in Superposition

# 摘要

> 大型语言模型（LLM）展现了惊人的 in-context learning（ICL）能力。本研究揭示了一个有趣的现象：LLM 能在一次推理中同时处理多个不同的 ICL 任务，我们称之为“任务叠加”。通过实验，我们发现这种现象在不同规模的 LLM 中普遍存在，即使模型是逐个任务训练的。理论分析表明，这种能力源于 transformer 的强大表达力。我们还深入探讨了 LLM 如何在叠加中组合任务向量。此外，更大的模型能并行处理更多任务，并更精准地校准输出。这些发现不仅揭示了 LLM 的潜在能力，也强化了“LLM 是模拟器叠加”的观点，并引发了对同时执行任务机制的思考。

> Large Language Models (LLMs) have demonstrated remarkable in-context learning (ICL) capabilities. In this study, we explore a surprising phenomenon related to ICL: LLMs can perform multiple, computationally distinct ICL tasks simultaneously, during a single inference call, a capability we term "task superposition". We provide empirical evidence of this phenomenon across various LLM families and scales and show that this phenomenon emerges even if we train the model to in-context learn one task at a time. We offer theoretical explanations that this capability is well within the expressive power of transformers. We also explore how LLMs internally compose task vectors during superposition. Furthermore, we show that larger models can solve more ICL tasks in parallel, and better calibrate their output distribution. Our findings offer insights into the latent capabilities of LLMs, further substantiate the perspective of "LLMs as superposition of simulators", and raise questions about the mechanisms enabling simultaneous task execution.

[Arxiv](https://arxiv.org/abs/2410.05603)