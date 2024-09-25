# 针对比较评估任务微调 LLM

发布时间：2024年09月24日

`LLM理论` `机器学习`

> Finetuning LLMs for Comparative Assessment Tasks

# 摘要

> 自然语言生成的自动评估充满挑战。指令调整的 LLM 在无参考评估中表现出色，尤其在比较评估中。但成对比较的二次复杂性限制了其扩展性。为此，我们探索了在零-shot LLM 概率上应用比较策略的高效评估方法。我们设计了一个微调框架，使 LLM 的输出与比较概率的目标分布一致。通过软概率训练，我们的方法不仅提升了性能，还保持了高效比较的优势。

> Automated assessment in natural language generation is a challenging task. Instruction-tuned large language models (LLMs) have shown promise in reference-free evaluation, particularly through comparative assessment. However, the quadratic computational complexity of pairwise comparisons limits its scalability. To address this, efficient comparative assessment has been explored by applying comparative strategies on zero-shot LLM probabilities. We propose a framework for finetuning LLMs for comparative assessment to align the model's output with the target distribution of comparative probabilities. By training on soft probabilities, our approach improves state-of-the-art performance while maintaining high performance with an efficient subset of comparisons.

[Arxiv](https://arxiv.org/abs/2409.15979)