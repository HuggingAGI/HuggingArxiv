# BiDoRA：双层优化驱动的权重分解低秩适应

发布时间：2024年10月13日

`LLM理论` `机器学习`

> BiDoRA: Bi-level Optimization-Based Weight-Decomposed Low-Rank Adaptation

# 摘要

> 大型语言模型的参数高效微调 (PEFT) 因其灵活高效的特点，已成为将 LLM 应用于下游任务的热门选择。其中，加权分解低秩适应 (DoRA) 方法备受瞩目。DoRA 通过分解权重矩阵，保持与全微调相似的学习行为，填补了低秩适应与全微调之间的空白。然而，DoRA 虽表现出色，却增加了参数数量，可能引发过拟合问题。同时，大小和方向的同步优化导致梯度更新耦合，限制了学习能力。为此，我们提出 BiDoRA，一种双层优化 PEFT 方法。BiDoRA 在不同数据集上分别优化方向和大小，降低过拟合风险，并促进两者的解耦，实现更灵活的梯度更新。在涵盖自然语言理解、生成和令牌分类的十四个数据集上的测试表明，BiDoRA 显著优于 DoRA 及其他 PEFT 方法，展现了其卓越性能。BiDoRA 代码已公开，详见 https://anonymous.4open.science/r/BiDoRA-5D31。

> Parameter-efficient fine-tuning (PEFT) of large language models (LLMs) has gained considerable attention as a flexible and efficient way of adapting LLMs to downstream tasks. Among these methods, weighted decomposed low-rank adaptation (DoRA) has emerged as a promising approach. DoRA bridges the gap between low-rank adaptation (LoRA) and full fine-tuning (FT) by decomposing the weight matrices into magnitude and direction components, thereby maintaining learning behavior similar to FT. Although DoRA shows encouraging performance, it introduces additional parameters compared to LoRA, which potentially increases the risk of overfitting. Moreover, optimizing magnitude and direction simultaneously leads to a coupled gradient updating pattern for both components, limiting its learning capacity. To overcome these limitations, we propose BiDoRA, a bi-level optimization-based PEFT method. In BiDoRA, the direction and magnitude components are optimized on two distinct datasets at different optimization levels, mitigating the risk of overfitting. Additionally, the asynchronous optimization of the two components promotes their decoupling, allowing for more flexible gradient updates suitable for various downstream tasks. Evaluation of BiDoRA on fourteen datasets spanning natural language understanding, natural language generation, and token classification reveals that it significantly outperforms DoRA and other PEFT methods. The superior performance of BiDoRA underscores its effectiveness. The code for BiDoRA is available at https://anonymous.4open.science/r/BiDoRA-5D31.

[Arxiv](https://arxiv.org/abs/2410.09758)