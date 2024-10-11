# 大型语言模型如何在（多轮）代码生成中进行推理？

发布时间：2024年10月10日

`LLM应用` `软件开发` `人工智能`

> What Makes Large Language Models Reason in (Multi-Turn) Code Generation?

# 摘要

> 链式思维等提示技术已成为提升 LLM 输出的热门手段。然而，在代码生成领域，其机制与效果仍待深入探究。我们深入研究了多种提示策略，特别关注多轮自动重新提示与计算需求。通过系统分解推理、指令与执行反馈提示，我们在 CodeContests 与 TACO 基准上对不同 LLM 进行了全面测试。研究发现，某些策略能在各模型中稳定提升性能，无论采样预算大小。进一步微调这些策略，使模型内化推理过程，显著提升多轮代码生成的性能与可扩展性。

> Prompting techniques such as chain-of-thought have established themselves as a popular vehicle for improving the outputs of large language models (LLMs). For code generation, however, their exact mechanics and efficacy are under-explored. We thus investigate the effects of a wide range of prompting strategies with a focus on automatic re-prompting over multiple turns and computational requirements. After systematically decomposing reasoning, instruction, and execution feedback prompts, we conduct an extensive grid search on the competitive programming benchmarks CodeContests and TACO for multiple LLM families and sizes (Llama 3.0 and 3.1, 8B, 70B, 405B, and GPT-4o). Our study reveals strategies that consistently improve performance across all models with small and large sampling budgets. We then show how finetuning with such an optimal configuration allows models to internalize the induced reasoning process and obtain improvements in performance and scalability for multi-turn code generation.

[Arxiv](https://arxiv.org/abs/2410.08105)