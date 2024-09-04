# 借助大型语言模型提升源代码安全：解析难题，打造可靠修复方案

发布时间：2024年08月31日

`LLM应用` `软件开发`

> Enhancing Source Code Security with LLMs: Demystifying The Challenges and Generating Reliable Repairs

# 摘要

> 随着AI计算的飞速发展，大型语言模型（LLMs）的进步带来了安全领域的明确指导挑战。本文深入探讨了LLM全流程中的三大技术难题：数据收集与标注、系统设计与学习、性能评估。为此，我们推出了\texttt{SecRepair}系统，该系统能精准识别、详细描述并自动修复代码漏洞。附带的实用指南涵盖了数据准备、模型选择与适应、评估流程。\texttt{SecRepair}通过强化学习微调，结合语义奖励，显著提升了代码安全修复效果。实证分析表明，相较于其他LLM，\texttt{SecRepair}在强化学习训练下，安全代码修复性能提升了12\%。此外，该系统还能针对真实测试案例，生成可靠、功能完善且可编译的安全代码修复方案，并通过自动化评估指标验证其效能。

> With the recent unprecedented advancements in Artificial Intelligence (AI) computing, progress in Large Language Models (LLMs) is accelerating rapidly, presenting challenges in establishing clear guidelines, particularly in the field of security. That being said, we thoroughly identify and describe three main technical challenges in the security and software engineering literature that spans the entire LLM workflow, namely; \textbf{\textit{(i)}} Data Collection and Labeling; \textbf{\textit{(ii)}} System Design and Learning; and \textbf{\textit{(iii)}} Performance Evaluation. Building upon these challenges, this paper introduces \texttt{SecRepair}, an instruction-based LLM system designed to reliably \textit{identify}, \textit{describe}, and automatically \textit{repair} vulnerable source code. Our system is accompanied by a list of actionable guides on \textbf{\textit{(i)}} Data Preparation and Augmentation Techniques; \textbf{\textit{(ii)}} Selecting and Adapting state-of-the-art LLM Models; \textbf{\textit{(iii)}} Evaluation Procedures. \texttt{SecRepair} uses a reinforcement learning-based fine-tuning with a semantic reward that caters to the functionality and security aspects of the generated code. Our empirical analysis shows that \texttt{SecRepair} achieves a \textit{12}\% improvement in security code repair compared to other LLMs when trained using reinforcement learning. Furthermore, we demonstrate the capabilities of \texttt{SecRepair} in generating reliable, functional, and compilable security code repairs against real-world test cases using automated evaluation metrics.

[Arxiv](https://arxiv.org/abs/2409.00571)