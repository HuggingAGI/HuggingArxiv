# T3：一种创新的零-shot 迁移学习框架，通过在辅助任务上迭代训练，最终实现目标任务。

发布时间：2024年09月26日

`LLM应用` `信息处理`

> T3: A Novel Zero-shot Transfer Learning Framework Iteratively Training on an Assistant Task for a Target Task

# 摘要

> 长文本摘要对于处理海量信息至关重要，但 GPT 和 LLaMA 等大型语言模型 (LLM) 仍面临挑战，主要因为开源训练数据不足和上下文细节要求高。为此，我们推出了 T3，一种创新的零-shot 迁移学习框架，通过在辅助任务上迭代训练 LLM，以完成目标任务。T3 利用问答作为辅助任务，成功应用于长文本摘要，并在多个数据集上显著提升了性能，ROUGE 提高近 14%，BLEU 提高 35%，Factscore 提高 16%，展示了其在多种任务组合中的巨大潜力。

> Long text summarization, gradually being essential for efficiently processing large volumes of information, stays challenging for Large Language Models (LLMs) such as GPT and LLaMA families because of the insufficient open-sourced training datasets and the high requirement of contextual details dealing. To address the issue, we design a novel zero-shot transfer learning framework, abbreviated as T3, to iteratively training a baseline LLM on an assistant task for the target task, where the former should own richer data resources and share structural or semantic similarity with the latter. In practice, T3 is approached to deal with the long text summarization task by utilizing question answering as the assistant task, and further validated its effectiveness on the BBC summary, NarraSum, FairytaleQA, and NLQuAD datasets, with up to nearly 14% improvement in ROUGE, 35% improvement in BLEU, and 16% improvement in Factscore compared to three baseline LLMs, demonstrating its potential for more assistant-target task combinations.

[Arxiv](https://arxiv.org/abs/2409.17640)