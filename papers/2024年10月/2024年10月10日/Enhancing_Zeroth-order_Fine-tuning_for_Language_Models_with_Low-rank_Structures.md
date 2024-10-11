# 利用低秩结构提升语言模型的零阶微调效果

发布时间：2024年10月10日

`LLM理论` `人工智能` `计算机科学`

> Enhancing Zeroth-order Fine-tuning for Language Models with Low-rank Structures

# 摘要

> 参数高效微调 (PEFT) 在调整大型语言模型 (LLM) 时显著降低了内存成本。然而，传统的一阶微调算法在长上下文任务中因需存储激活值而产生大量内存开销。零阶算法通过有限差分近似梯度，无需存储激活值，但现有方法难以捕捉低秩梯度结构。本文提出低秩 ZO 算法 (LOZO)，有效捕捉 LLM 中的低秩结构，并提供收敛性保证。LOZO 还能与动量技术集成，几乎不增加内存成本。实验表明，LOZO 及其动量变体在各种任务中优于现有 ZO 方法，接近一阶算法性能。

> Parameter-efficient fine-tuning (PEFT) significantly reduces memory costs when adapting large language models (LLMs) for downstream applications. However, traditional first-order (FO) fine-tuning algorithms incur substantial memory overhead due to the need to store activation values for back-propagation during gradient computation, particularly in long-context fine-tuning tasks. Zeroth-order (ZO) algorithms offer a promising alternative by approximating gradients using finite differences of function values, thus eliminating the need for activation storage. Nevertheless, existing ZO methods struggle to capture the low-rank gradient structure common in LLM fine-tuning, leading to suboptimal performance. This paper proposes a low-rank ZO gradient estimator and introduces a novel low-rank ZO algorithm (LOZO) that effectively captures this structure in LLMs. We provide convergence guarantees for LOZO by framing it as a subspace optimization method. Additionally, its low-rank nature enables LOZO to integrate with momentum techniques while incurring negligible extra memory costs. Extensive experiments across various model sizes and downstream tasks demonstrate that LOZO and its momentum-based variant outperform existing ZO methods and closely approach the performance of FO algorithms.

[Arxiv](https://arxiv.org/abs/2410.07698)