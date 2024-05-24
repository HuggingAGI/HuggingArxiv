# ConTrans：借助概念移植，实现从弱到强的对齐工程优化

发布时间：2024年05月22日

`LLM理论

这篇论文探讨了大型语言模型（LLM）与人类目标、价值观和意图的对齐问题，并提出了一种新的框架——ConTrans。该框架通过概念移植实现从弱到强的对齐转移，这是一种理论上的创新，旨在降低对齐训练的计算成本。因此，这篇论文更偏向于LLM的理论研究，特别是关于模型对齐和概念移植的理论探讨。` `人工智能` `模型对齐`

> ConTrans: Weak-to-Strong Alignment Engineering via Concept Transplantation

# 摘要

> 为了确保大型语言模型（LLM）与人类目标、价值观和意图保持一致，同时降低其对齐训练的计算成本，我们提出了ConTrans框架。该框架通过概念移植实现从弱到强的对齐转移。ConTrans从已对齐的弱LLM中提炼概念向量，并通过仿射变换使其适应未对齐的强LLM。随后，这些概念向量被移植到目标LLM的残差流中。实验证明，ConTrans能成功地将多种对齐概念从7B模型移植到13B和70B模型，并在真实性上超越了指令调整模型。这一成果不仅验证了跨LLM家族和同一LLM家族内概念移植的有效性，也为实现弱到强对齐泛化和控制提供了新思路。

> Ensuring large language models (LLM) behave consistently with human goals, values, and intentions is crucial for their safety but yet computationally expensive. To reduce the computational cost of alignment training of LLMs, especially for those with a huge number of parameters, and to reutilize learned value alignment, we propose ConTrans, a novel framework that enables weak-to-strong alignment transfer via concept transplantation. From the perspective of representation engineering, ConTrans refines concept vectors in value alignment from a source LLM (usually a weak yet aligned LLM). The refined concept vectors are then reformulated to adapt to the target LLM (usually a strong yet unaligned base LLM) via affine transformation. In the third step, ConTrans transplants the reformulated concept vectors into the residual stream of the target LLM. Experiments demonstrate the successful transplantation of a wide range of aligned concepts from 7B models to 13B and 70B models across multiple LLMs and LLM families. Remarkably, ConTrans even surpasses instruction-tuned models in terms of truthfulness. Experiment results validate the effectiveness of both inter-LLM-family and intra-LLM-family concept transplantation. Our work successfully demonstrates an alternative way to achieve weak-to-strong alignment generalization and control.

[Arxiv](https://arxiv.org/abs/2405.13578)