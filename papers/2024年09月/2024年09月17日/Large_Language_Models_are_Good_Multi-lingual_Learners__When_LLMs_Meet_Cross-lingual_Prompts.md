# 大型语言模型在多语言学习中表现出色：当 LLM 遇到跨语言提示时，它们展现了卓越的学习能力。

发布时间：2024年09月17日

`LLM应用` `软件开发` `数据处理`

> Large Language Models are Good Multi-lingual Learners : When LLMs Meet Cross-lingual Prompts

# 摘要

> 随着大型语言模型 (LLM) 的兴起，生成基于规则的实际应用数据变得更加便捷。然而，自然语言的模糊性和复杂规则集，特别是在长篇上下文中，常使 LLM 难以完全遵循所有规则，往往至少遗漏一项。为此，我们创新性地提出了多语言提示策略 MLPrompt，通过自动将 LLM 难以遵循的规则翻译成其他语言，增强其关注度。实验显示，MLPrompt 在多个任务的公共数据集上，性能超越了如 Chain of Thought、Tree of Thought 和 Self-Consistency 等顶尖提示方法。我们还构建了一个集成 MLPrompt 与自动检查机制的框架，专门用于结构化数据生成，并通过文本到 MIP 实例进行了实证研究。此外，该框架已扩展至文本到 SQL，展示了其在结构化数据合成方面的卓越能力。

> With the advent of Large Language Models (LLMs), generating rule-based data for real-world applications has become more accessible. Due to the inherent ambiguity of natural language and the complexity of rule sets, especially in long contexts, LLMs often struggle to follow all specified rules, frequently omitting at least one. To enhance the reasoning and understanding of LLMs on long and complex contexts, we propose a novel prompting strategy Multi-Lingual Prompt, namely MLPrompt, which automatically translates the error-prone rule that an LLM struggles to follow into another language, thus drawing greater attention to it. Experimental results on public datasets across various tasks have shown MLPrompt can outperform state-of-the-art prompting methods such as Chain of Thought, Tree of Thought, and Self-Consistency. Additionally, we introduce a framework integrating MLPrompt with an auto-checking mechanism for structured data generation, with a specific case study in text-to-MIP instances. Further, we extend the proposed framework for text-to-SQL to demonstrate its generation ability towards structured data synthesis.

[Arxiv](https://arxiv.org/abs/2409.11056)