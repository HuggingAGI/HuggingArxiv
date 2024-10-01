# 利用大型语言模型的蒙特卡罗树搜索实现零-shot多跳问答

发布时间：2024年09月28日

`LLM应用` `人工智能` `问答系统`

> Zero-Shot Multi-Hop Question Answering via Monte-Carlo Tree Search with Large Language Models

# 摘要

> 大型语言模型 (LLM) 的最新进展对多跳问答 (MHQA) 领域产生了重大影响，但自回归性质带来的错误累积问题仍待解决。本文提出了基于蒙特卡罗树搜索 (MCTS) 的零-shot 多跳问答框架 (MZQA)，有效减少了推理过程中的错误传播。我们创新性地采用了零-shot 提示方法，无需领域专业知识的手工示例，并引入了行为克隆技术 (MZQA-BC)，推理速度提升 10 倍以上，性能几乎无损。实验结果表明，MZQA 在多个标准基准上均优于现有框架。

> Recent advances in large language models (LLMs) have significantly impacted the domain of multi-hop question answering (MHQA), where systems are required to aggregate information and infer answers from disparate pieces of text. However, the autoregressive nature of LLMs inherently poses a challenge as errors may accumulate if mistakes are made in the intermediate reasoning steps. This paper introduces Monte-Carlo tree search for Zero-shot multi-hop Question Answering (MZQA), a framework based on Monte-Carlo tree search (MCTS) to identify optimal reasoning paths in MHQA tasks, mitigating the error propagation from sequential reasoning processes. Unlike previous works, we propose a zero-shot prompting method, which relies solely on instructions without the support of hand-crafted few-shot examples that typically require domain expertise. We also introduce a behavioral cloning approach (MZQA-BC) trained on self-generated MCTS inference trajectories, achieving an over 10-fold increase in reasoning speed with bare compromise in performance. The efficacy of our method is validated on standard benchmarks such as HotpotQA, 2WikiMultihopQA, and MuSiQue, demonstrating that it outperforms existing frameworks.

[Arxiv](https://arxiv.org/abs/2409.19382)