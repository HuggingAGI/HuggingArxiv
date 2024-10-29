# LLM 初始化的可微因果发现

发布时间：2024年10月28日

`LLM应用` `因果发现` `科学研究`

> LLM-initialized Differentiable Causal Discovery

# 摘要

> 随机变量之间因果关系的发现是一个重要但具有挑战性的问题，在许多科学领域都有应用。可微因果发现（DCD）方法在从观测数据中揭示因果关系方面是有效的；然而，这些方法往往解释性有限，并在纳入特定领域的先验知识方面面临挑战。相比之下，基于大型语言模型（LLM）的因果发现方法最近已被证明能够为因果发现提供有用的先验，但在正式因果推理方面存在困难。在本文中，我们提出了 LLM-DCD，它使用 LLM 来初始化 DCD 方法的最大似然目标函数的优化，从而将强大的先验纳入发现方法。为了实现这种初始化，我们将目标函数设计为仅依赖于因果图的明确定义的邻接矩阵作为其唯一的变分参数。直接优化明确定义的邻接矩阵为因果发现提供了一种更具解释性的方法。此外，我们证明了我们的方法在关键基准数据集上比最先进的替代方法具有更高的准确性，并提供了经验证据，表明初始化的质量直接影响我们 DCD 方法的最终输出质量。LLM-DCD 为像 DCD 这样的传统因果发现方法开辟了新的机会，使其能够受益于 LLM 因果推理能力的未来改进。

> The discovery of causal relationships between random variables is an important yet challenging problem that has applications across many scientific domains. Differentiable causal discovery (DCD) methods are effective in uncovering causal relationships from observational data; however, these approaches often suffer from limited interpretability and face challenges in incorporating domain-specific prior knowledge. In contrast, Large Language Models (LLMs)-based causal discovery approaches have recently been shown capable of providing useful priors for causal discovery but struggle with formal causal reasoning. In this paper, we propose LLM-DCD, which uses an LLM to initialize the optimization of the maximum likelihood objective function of DCD approaches, thereby incorporating strong priors into the discovery method. To achieve this initialization, we design our objective function to depend on an explicitly defined adjacency matrix of the causal graph as its only variational parameter. Directly optimizing the explicitly defined adjacency matrix provides a more interpretable approach to causal discovery. Additionally, we demonstrate higher accuracy on key benchmarking datasets of our approach compared to state-of-the-art alternatives, and provide empirical evidence that the quality of the initialization directly impacts the quality of the final output of our DCD approach. LLM-DCD opens up new opportunities for traditional causal discovery methods like DCD to benefit from future improvements in the causal reasoning capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.21141)