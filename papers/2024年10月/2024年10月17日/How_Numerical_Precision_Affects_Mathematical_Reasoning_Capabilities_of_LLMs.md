# 数值精度对 LLMs 数学推理能力的影响

发布时间：2024年10月17日

`LLM理论` `人工智能`

> How Numerical Precision Affects Mathematical Reasoning Capabilities of LLMs

# 摘要

> 尽管 Transformer 大型语言模型 (LLM) 在各领域表现出色，但其数学能力的提升仍面临挑战。本文深入分析了 LLM 的数学能力，特别关注其算术表现。研究发现，数值精度是影响其数学任务表现的关键。低精度 Transformer 难以应对复杂算术任务，除非模型规模大幅增加。而标准精度 Transformer 则能以更小模型高效处理这些任务。通过实证实验，我们进一步验证了这一理论，揭示了数值精度对算术任务的影响，为提升 LLM 的数学推理能力提供了重要启示。

> Despite the remarkable success of Transformer-based Large Language Models (LLMs) across various domains, understanding and enhancing their mathematical capabilities remains a significant challenge. In this paper, we conduct a rigorous theoretical analysis of LLMs' mathematical abilities, with a specific focus on their arithmetic performances. We identify numerical precision as a key factor that influences their effectiveness in mathematical tasks. Our results show that Transformers operating with low numerical precision fail to address arithmetic tasks, such as iterated addition and integer multiplication, unless the model size grows super-polynomially with respect to the input length. In contrast, Transformers with standard numerical precision can efficiently handle these tasks with significantly smaller model sizes. We further support our theoretical findings through empirical experiments that explore the impact of varying numerical precision on arithmetic tasks, providing valuable insights for improving the mathematical reasoning capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.13857)