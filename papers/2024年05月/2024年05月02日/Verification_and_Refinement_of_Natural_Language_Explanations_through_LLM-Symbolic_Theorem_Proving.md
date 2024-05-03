# 利用大型语言模型（LLM）中的符号定理证明技术，对自然语言解释进行验证与优化。

发布时间：2024年05月02日

`LLM应用` `逻辑推理`

> Verification and Refinement of Natural Language Explanations through LLM-Symbolic Theorem Proving

# 摘要

> 自然语言阐释已成为评价可解释性及多步自然语言推理（NLI）模型的标准。然而，验证 NLI 解释的合理性并非易事，这通常需要通过众包获取合适的数据集，既费时又易出错。为克服这些难题，本研究探讨了结合大型语言模型（LLMs）与定理证明器（TPs）来对自然语言阐释进行验证和细化的方法。我们提出了一个名为 Explanation-Refiner 的神经符号框架，该框架利用 LLMs 增强 TP，以生成形式化的解释性句子，并为 NLI 提供可能的推理策略。TP 用于确保解释的逻辑有效性，并为后续改进提供反馈。我们证明了 Explanation-Refiner 如何被用于评估顶尖 LLMs 的解释推理能力、自动形式化以及错误修正机制，并自动提升不同领域中复杂程度不一的人工注释解释的质量。

> Natural language explanations have become a proxy for evaluating explainable and multi-step Natural Language Inference (NLI) models. However, assessing the validity of explanations for NLI is challenging as it typically involves the crowd-sourcing of apposite datasets, a process that is time-consuming and prone to logical errors. To address existing limitations, this paper investigates the verification and refinement of natural language explanations through the integration of Large Language Models (LLMs) and Theorem Provers (TPs). Specifically, we present a neuro-symbolic framework, named Explanation-Refiner, that augments a TP with LLMs to generate and formalise explanatory sentences and suggest potential inference strategies for NLI. In turn, the TP is employed to provide formal guarantees on the logical validity of the explanations and to generate feedback for subsequent improvements. We demonstrate how Explanation-Refiner can be jointly used to evaluate explanatory reasoning, autoformalisation, and error correction mechanisms of state-of-the-art LLMs as well as to automatically enhance the quality of human-annotated explanations of variable complexity in different domains.

[Arxiv](https://arxiv.org/abs/2405.01379)