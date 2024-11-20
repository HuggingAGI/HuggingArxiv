# 婴儿代理：一种集成工具、由逻辑驱动且具有高性价比 API 使用的代理

发布时间：2024年11月01日

`Agent`

> Infant Agent: A Tool-Integrated, Logic-Driven Agent with Cost-Effective API Usage

# 摘要

> 尽管大型语言模型（LLMs）能力出众，但当下仍存在两大主要局限，	extbf{其一}：难以	extbf{自主解决现实世界中的工程问题}。	extbf{其二}：在	extbf{通过复杂逻辑问题进行推理时面临挑战}。为应对这些难题，我们研发了	extsc{婴儿代理}，它整合了任务感知功能、运算符、分层管理系统以及内存检索机制。这些组件协同作用，让大型语言模型能够持续进行扩展推理，高效处理复杂的多步骤任务，同时大幅降低 API 成本。借助	extsc{婴儿代理}，GPT-4o 在 SWE-bench-lite 数据集上的准确率从$\mathbf{0.33\%}$提升至$\mathbf{30\%}$，在 AIME-2024 数学竞赛中，将 GPT-4o 的准确率从$\mathbf{13.3\%}$提高到$\mathbf{37\%}$。

> Despite the impressive capabilities of large language models (LLMs), they currently exhibit two primary limitations, \textbf{uppercase\expandafter{\romannumeral 1}}: They struggle to \textbf{autonomously solve the real world engineering problem}. \textbf{uppercase\expandafter{\romannumeral 2}}: They remain \textbf{challenged in reasoning through complex logic problems}. To address these challenges, we developed the \textsc{Infant Agent}, integrating task-aware functions, operators, a hierarchical management system, and a memory retrieval mechanism. Together, these components enable large language models to sustain extended reasoning processes and handle complex, multi-step tasks efficiently, all while significantly reducing API costs. Using the \textsc{Infant Agent}, GPT-4o's accuracy on the SWE-bench-lite dataset rises from $\mathbf{0.33\%}$ to $\mathbf{30\%}$, and in the AIME-2024 mathematics competition, it increases GPT-4o's accuracy from $\mathbf{13.3\%}$ to $\mathbf{37\%}$.

[Arxiv](https://arxiv.org/abs/2411.01114)