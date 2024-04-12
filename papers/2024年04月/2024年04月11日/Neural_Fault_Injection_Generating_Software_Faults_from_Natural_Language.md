# 神经故障注入技术：利用自然语言制造软件缺陷

发布时间：2024年04月11日

`RAG` `软件工程` `人工智能`

> Neural Fault Injection: Generating Software Faults from Natural Language

# 摘要

> 传统软件故障注入技术虽根基深厚，但在模拟真实故障、个性化定制以及对大量人工操作和专业技能的依赖上存在局限。本研究提出了一种创新方法，通过结合大型语言模型（LLMs）和基于人类反馈的强化学习（RLHF），有效应对上述挑战。RLHF的应用突出了一个反复优化的过程，测试者可以对生成的故障进行反馈，进而提升LLM生成故障的能力，确保生成的故障情景更贴近实际操作中的风险。这一方法大幅降低了人工制定故障情景的劳动强度，使测试者能够专注于更高级的测试策略，为提升软件系统的可靠性开启了新的路径。

> Traditional software fault injection methods, while foundational, face limitations in adequately representing real-world faults, offering customization, and requiring significant manual effort and expertise. This paper introduces a novel methodology that harnesses the capabilities of Large Language Models (LLMs) augmented with Reinforcement Learning from Human Feedback (RLHF) to overcome these challenges. The usage of RLHF emphasizes an iterative refinement process, allowing testers to provide feedback on generated faults, which is then used to enhance the LLM's fault generation capabilities, ensuring the generation of fault scenarios that closely mirror actual operational risks. This innovative methodology aims to significantly reduce the manual effort involved in crafting fault scenarios as it allows testers to focus on higher-level testing strategies, hence paving the way to new possibilities for enhancing the dependability of software systems.

![神经故障注入技术：利用自然语言制造软件缺陷](../../../paper_images/2404.07491/x1.png)

[Arxiv](https://arxiv.org/abs/2404.07491)