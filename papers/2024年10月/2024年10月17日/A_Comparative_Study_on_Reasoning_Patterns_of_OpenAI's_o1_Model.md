# 探究 OpenAI o1 模型推理模式的对比研究

发布时间：2024年10月17日

`LLM应用` `人工智能` `软件开发`

> A Comparative Study on Reasoning Patterns of OpenAI's o1 Model

# 摘要

> 让大型语言模型 (LLM) 处理更复杂的任务（如编码和数学）已成为研究热点。随着 LLM 的发展，单纯增加参数已难以显著提升性能，且成本高昂。最近，OpenAI 的 o1 模型通过推理策略（测试时计算方法）显著提升了 LLM 的推理能力，但其机制仍待探索。我们通过 GPT-4o 在数学、编码和常识推理三个领域的基准测试中，对比了 o1 与现有方法（BoN、逐步 BoN、代理工作流和自我改进）。实验显示，o1 在多数数据集上表现最佳。对于搜索多样化响应的方法，奖励模型和搜索空间限制了其上限。将问题分解的方法中，代理工作流因领域特定提示而优于逐步 BoN。此外，我们总结了 o1 的六种推理模式，并进行了详细分析。

> Enabling Large Language Models (LLMs) to handle a wider range of complex tasks (e.g., coding, math) has drawn great attention from many researchers. As LLMs continue to evolve, merely increasing the number of model parameters yields diminishing performance improvements and heavy computational costs. Recently, OpenAI's o1 model has shown that inference strategies (i.e., Test-time Compute methods) can also significantly enhance the reasoning capabilities of LLMs. However, the mechanisms behind these methods are still unexplored. In our work, to investigate the reasoning patterns of o1, we compare o1 with existing Test-time Compute methods (BoN, Step-wise BoN, Agent Workflow, and Self-Refine) by using OpenAI's GPT-4o as a backbone on general reasoning benchmarks in three domains (i.e., math, coding, commonsense reasoning). Specifically, first, our experiments show that the o1 model has achieved the best performance on most datasets. Second, as for the methods of searching diverse responses (e.g., BoN), we find the reward models' capability and the search space both limit the upper boundary of these methods. Third, as for the methods that break the problem into many sub-problems, the Agent Workflow has achieved better performance than Step-wise BoN due to the domain-specific system prompt for planning better reasoning processes. Fourth, it is worth mentioning that we have summarized six reasoning patterns of o1, and provided a detailed analysis on several reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2410.13639)