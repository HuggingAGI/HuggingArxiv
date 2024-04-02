# 在语言模型中，我们追求概念性的理解和无偏见的推理能力。

发布时间：2024年03月29日

`LLM理论` `人工智能` `认知科学`

> Conceptual and Unbiased Reasoning in Language Models

# 摘要

> 概念推理，即在抽象层面进行高层次推理的能力，是人类认知泛化的关键。但目前对大型语言模型在这方面的研究尚不充分。本研究旨在填补这一空白，提出了一个创新框架，迫使模型在抽象问题上进行概念推理，并在可验证的符号空间中给出解答。通过这一框架的分析，我们发现现有的大型语言模型在概念推理方面存在不足，相较于直接推理方法，其在多项基准测试中的表现下降了9%至28%。我们进一步探讨了如何提升模型性能，因为高级抽象推理对于公正和可泛化的决策至关重要。我们提出了两种方法，一是通过生成类似问题来增强模型对相似推理路径的理解，二是引导模型进行自我优化。实验结果显示，这些方法能够提升模型在概念推理方面的表现8%至11%，构建了一个更加稳健、依赖归纳偏见更少的推理系统。

> Conceptual reasoning, the ability to reason in abstract and high-level perspectives, is key to generalization in human cognition. However, limited study has been done on large language models' capability to perform conceptual reasoning. In this work, we bridge this gap and propose a novel conceptualization framework that forces models to perform conceptual reasoning on abstract questions and generate solutions in a verifiable symbolic space. Using this framework as an analytical tool, we show that existing large language models fall short on conceptual reasoning, dropping 9% to 28% on various benchmarks compared to direct inference methods. We then discuss how models can improve since high-level abstract reasoning is key to unbiased and generalizable decision-making. We propose two techniques to add trustworthy induction signals by generating familiar questions with similar underlying reasoning paths and asking models to perform self-refinement. Experiments show that our proposed techniques improve models' conceptual reasoning performance by 8% to 11%, achieving a more robust reasoning system that relies less on inductive biases.

[Arxiv](https://arxiv.org/abs/2404.00205)