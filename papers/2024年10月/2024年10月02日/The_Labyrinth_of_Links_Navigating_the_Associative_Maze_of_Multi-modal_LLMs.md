# 链接迷宫：探索多模态大型语言模型的关联网络

发布时间：2024年10月02日

`LLM应用` `人工智能`

> The Labyrinth of Links: Navigating the Associative Maze of Multi-modal LLMs

# 摘要

> 多模态大型语言模型（MLLM）虽然表现出色，但与人类智能相比仍存在诸多不足，如幻觉现象。为此，社区努力构建了包含复杂任务的大型基准。本文提出对“关联”这一基本但常被忽视的智能进行基准测试，即人类将观察与记忆联系的能力。我们设计了基于形容词和动词语义的关联任务标准基准，并提出了一种无需标注的便捷构建方法，同时通过严格的数据提炼过程确保数据质量。基于此，我们构建了单步、同步和异步三个级别的关联任务。此外，我们全面评估了MLLM的零样本关联能力，涵盖多种模型和记忆策略。结果显示，当前开源MLLM在关联任务上表现不佳，即使是最先进的GPT-4V也与人类存在显著差距。我们相信，这一基准将为未来MLLM研究奠定基础。数据和代码详见：https://mvig-rhos.com/llm_inception。

> Multi-modal Large Language Models (MLLMs) have exhibited impressive capability. However, recently many deficiencies of MLLMs have been found compared to human intelligence, $\textit{e.g.}$, hallucination. To drive the MLLMs study, the community dedicated efforts to building larger benchmarks with complex tasks. In this paper, we propose benchmarking an essential but usually overlooked intelligence: $\textbf{association}$, a human's basic capability to link observation and prior practice memory. To comprehensively investigate MLLM's performance on the association, we formulate the association task and devise a standard benchmark based on adjective and verb semantic concepts. Instead of costly data annotation and curation, we propose a convenient $\textbf{annotation-free}$ construction method transforming the general dataset for our association tasks. Simultaneously, we devise a rigorous data refinement process to eliminate confusion in the raw dataset. Building on this database, we establish three levels of association tasks: single-step, synchronous, and asynchronous associations. Moreover, we conduct a comprehensive investigation into the MLLMs' zero-shot association capabilities, addressing multiple dimensions, including three distinct memory strategies, both open-source and closed-source MLLMs, cutting-edge Mixture-of-Experts (MoE) models, and the involvement of human experts. Our systematic investigation shows that current open-source MLLMs consistently exhibit poor capability in our association tasks, even the currently state-of-the-art GPT-4V(vision) also has a significant gap compared to humans. We believe our benchmark would pave the way for future MLLM studies. $\textit{Our data and code are available at:}$ https://mvig-rhos.com/llm_inception.

[Arxiv](https://arxiv.org/abs/2410.01417)