# 大型语言模型中的代码组合难题——从概率角度解析

发布时间：2024年09月26日

`LLM理论` `软件开发` `人工智能`

> Compositional Hardness of Code in Large Language Models -- A Probabilistic Perspective

# 摘要

> 在 LLM 中，处理代码生成等复杂任务时，通常会在上下文窗口内为整个任务采样一个解决方案。已有研究表明，上下文中的子任务分解（思维链）有助于任务解决。然而，我们发现 LLM 在同一上下文内处理多个子任务的能力有限，即存在上下文组合难度，这使得在多代理系统中分布问题更具优势。我们通过生成复杂度指标量化了这种难度，发现同一上下文内解决组合问题的复杂度与多代理分布相比存在指数级差距。我们的研究通过理论和实证双重验证了这一发现。

> A common practice in large language model (LLM) usage for complex analytical tasks such as code generation, is to sample a solution for the entire task within the model's context window. Previous works have shown that subtask decomposition within the model's context (chain of thought), is beneficial for solving such tasks. In this work, we point a limitation of LLMs' ability to perform several sub-tasks within the same context window - an in-context hardness of composition, pointing to an advantage for distributing a decomposed problem in a multi-agent system of LLMs. The hardness of composition is quantified by a generation complexity metric, i.e., the number of LLM generations required to sample at least one correct solution. We find a gap between the generation complexity of solving a compositional problem within the same context relative to distributing it among multiple agents, that increases exponentially with the solution's length. We prove our results theoretically and demonstrate them empirically.

[Arxiv](https://arxiv.org/abs/2409.18028)