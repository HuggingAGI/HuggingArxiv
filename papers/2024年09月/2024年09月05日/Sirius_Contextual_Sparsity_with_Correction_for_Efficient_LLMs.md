# Sirius：结合上下文稀疏与修正，打造高效 LLM

发布时间：2024年09月05日

`LLM应用` `人工智能` `软件开发`

> Sirius: Contextual Sparsity with Correction for Efficient LLMs

# 摘要

> 随着 LLM 的普及，推理效率愈发关键。为降低推理成本，多种近似方法应运而生，其中上下文稀疏性 (CS) 因其无需训练且能在不损质量的前提下实现高压缩率而备受瞩目。然而，全面评估显示，CS 虽在提示理解任务中表现出色，但在推理、演绎及知识型任务中却显著拖累模型性能。尽管如此，我们发现稀疏模型的问题解决逻辑与原模型相近，仅需少量标记校正即可恢复性能。为此，我们推出了 Sirius，一种高效校正机制，能在保持效率优势的同时大幅提升 CS 模型在推理任务中的表现。Sirius 在 6 个模型上针对 8 个复杂生成任务（涵盖推理、数学和编码）进行了测试，效果显著且稳定。此外，我们精心实现了 Sirius 系统，使其在 8B 模型上芯片延迟减少约 20%，70B 模型卸载延迟减少 35%。Sirius 的代码已在 https://github.com/Infini-AI-Lab/Sirius.git 开源。

> With the blossom of large language models (LLMs), inference efficiency becomes increasingly important. Various approximation methods are proposed to reduce the cost at inference time. Contextual Sparsity (CS) is appealing for its training-free nature and its ability to reach a higher compression ratio seemingly without quality degradation. However, after a comprehensive evaluation of contextual sparsity methods on various complex generation tasks, we find that although CS succeeds in prompt-understanding tasks, CS significantly degrades the model performance for reasoning, deduction, and knowledge-based tasks. Despite the gap in end-to-end accuracy, we observed that sparse models often share general problem-solving logic and require only a few token corrections to recover the original model performance. This paper introduces Sirius, an efficient correction mechanism, which significantly recovers CS models quality on reasoning tasks while maintaining its efficiency gain. Sirius is evaluated on 6 models with 8 difficult generation tasks in reasoning, math, and coding and shows consistent effectiveness and efficiency. Also, we carefully develop a system implementation for Sirius and show that Sirius achieves roughly 20% reduction in latency for 8B model on-chip and 35% reduction for 70B model offloading. We open-source our implementation of Sirius at https://github.com/Infini-AI-Lab/Sirius.git.

[Arxiv](https://arxiv.org/abs/2409.03856)