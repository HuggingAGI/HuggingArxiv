# 超越思维链：大型语言模型链式X范式全面解析

发布时间：2024年04月24日

`LLM理论

这篇论文主要探讨了基于 Chain-of-Thought (CoT) 方法的扩展，即 Chain-of-X (CoX) 方法，这些方法旨在解决大型语言模型 (LLMs) 在不同领域和任务中的挑战。论文对 CoX 方法进行了全面的综述，并根据节点分类和应用任务进行了分类。这表明论文主要关注的是 LLMs 的理论发展和应用框架，而不是具体的 Agent 行为、RAG（检索增强生成）技术或特定的 LLM 应用实例。因此，将其归类为LLM理论是合适的。` `人工智能`

> Beyond Chain-of-Thought: A Survey of Chain-of-X Paradigms for LLMs

# 摘要

> Chain-of-Thought (CoT) 方法因其能激发大型语言模型 (LLMs) 的强大推理能力而广受欢迎。基于 CoT 的顺序思维结构，一系列名为 Chain-of-X (CoX) 的方法应运而生，旨在解决跨领域和任务中与 LLMs 相关的多种挑战。本文对不同情境下 LLMs 的 CoX 方法进行了全面综述，特别依据节点分类（即 CoX 中的 X）和应用任务进行分类。同时，我们探讨了现有 CoX 方法的研究成果及其影响，并展望了未来的发展方向。本综述旨在为希望将 CoT 概念拓展至更广泛应用场景的研究者提供一份详尽且及时的参考资料。

> Chain-of-Thought (CoT) has been a widely adopted prompting method, eliciting impressive reasoning abilities of Large Language Models (LLMs). Inspired by the sequential thought structure of CoT, a number of Chain-of-X (CoX) methods have been developed to address various challenges across diverse domains and tasks involving LLMs. In this paper, we provide a comprehensive survey of Chain-of-X methods for LLMs in different contexts. Specifically, we categorize them by taxonomies of nodes, i.e., the X in CoX, and application tasks. We also discuss the findings and implications of existing CoX methods, as well as potential future directions. Our survey aims to serve as a detailed and up-to-date resource for researchers seeking to apply the idea of CoT to broader scenarios.

[Arxiv](https://arxiv.org/abs/2404.15676)