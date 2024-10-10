# Auto-Evolve：借助自我推理框架，提升大型语言模型的表现

发布时间：2024年10月08日

`LLM应用` `人工智能`

> Auto-Evolve: Enhancing Large Language Model's Performance via Self-Reasoning Framework

# 摘要

> 近期，Chain-of-Thought (CoT) 和 Self-Discover 等提示工程策略显著提升了大型语言模型 (LLM) 的推理能力。然而，这些最先进的提示策略依赖于单一或固定的静态推理模块，如“逐步思考”或“分解问题”，这限制了模型应对多样问题的灵活性。为此，我们提出了 Auto-Evolve 框架，使 LLM 能够动态生成推理模块和行动计划，显著超越现有 SOTA 方法。在 BigBench-Hard (BBH) 数据集上，Auto-Evolve 在 Claude 2.0、Claude 3 Sonnet、Mistral Large 和 GPT 4 上均表现优异，平均提升 7\%，最高达 10.4\%。该框架的创新之处在于：a) 动态生成与人类推理范式对齐的模块，无需预定义模板；b) 引入迭代细化组件，逐步优化指令，平均提升 2.8\% 性能。

> Recent advancements in prompt engineering strategies, such as Chain-of-Thought (CoT) and Self-Discover, have demonstrated significant potential in improving the reasoning abilities of Large Language Models (LLMs). However, these state-of-the-art (SOTA) prompting strategies rely on single or fixed set of static seed reasoning modules like \emph{"think step by step"} or \emph{"break down this problem"} intended to simulate human approach to problem-solving. This constraint limits the flexibility of models in tackling diverse problems effectively. In this paper, we introduce Auto-Evolve, a novel framework that enables LLMs to self-create dynamic reasoning modules and downstream action plan, resulting in significant improvements over current SOTA methods. We evaluate Auto-Evolve on the challenging BigBench-Hard (BBH) dataset with Claude 2.0, Claude 3 Sonnet, Mistral Large, and GPT 4, where it consistently outperforms the SOTA prompt strategies. Auto-Evolve outperforms CoT by up to 10.4\% and on an average by 7\% across these four models. Our framework introduces two innovations: a) Auto-Evolve dynamically generates reasoning modules for each task while aligning with human reasoning paradigm, thus eliminating the need for predefined templates. b) We introduce an iterative refinement component, that incrementally refines instruction guidance for LLMs and helps boost performance by average 2.8\% compared to doing it in a single step.

[Arxiv](https://arxiv.org/abs/2410.06328)