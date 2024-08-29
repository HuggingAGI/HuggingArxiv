# 通过检索增强指令调优，我们构建了一个自动化过程工程计算的工具链问题解决框架，该框架融入了可归因的反思机制。

发布时间：2024年08月28日

`Agent` `过程工程`

> Retrieval-Augmented Instruction Tuning for Automated Process Engineering Calculations : A Tool-Chaining Problem-Solving Framework with Attributable Reflection

# 摘要

> 在当前技术背景下，缺乏一个基础AI模型来应对过程工程计算的挑战。为此，我们创新性地提出了一个自主代理框架，该框架通过检索增强指令调优（RAIT）技术，强化了开放且可定制的小代码语言模型（SLMs），使其能够高效处理这些计算任务。该框架结合了指令调优的代码SLMs与检索增强代码生成（RACG）技术，利用外部工具，实现了从自然语言规范中自动生成、调试和优化代码的功能。这一方法不仅弥补了现有AI模型在专门过程工程任务上的不足，还带来了可解释性、知识编辑和成本效益等多重优势。同时，我们精心构建了化学和过程工程领域的自定义数据集，有效解决了数据稀缺问题。实验证明，我们的框架在性能上与大型专有模型不相上下，充分展现了其高效与实用性。

> The current technology landscape lacks a foundational AI model for solving process engineering calculations. In this work, we introduce a novel autonomous agent framework leveraging Retrieval-Augmented Instruction-Tuning (RAIT) to enhance open, customizable small code language models (SLMs) for these calculations. By combining instruction tuned code SLMs with Retrieval-Augmented Code Generation (RACG) using external tools, the agent generates, debugs, and optimizes code from natural language specifications. Our approach addresses the limitations of the current lack of a foundational AI model for specialized process engineering tasks and offers benefits of explainability, knowledge editing, and cost-effectiveness. Additionally, we curate custom datasets of chemical and process engineering problems and solutions to overcome data scarcity. Experimental results show that our framework matches the performance of large-scale proprietary models on benchmark datasets, proving its effectiveness and usability.

[Arxiv](https://arxiv.org/abs/2408.15866)