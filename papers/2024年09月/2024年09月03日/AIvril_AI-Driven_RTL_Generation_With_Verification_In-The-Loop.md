# AIvril：AI 驱动，RTL 生成与实时验证一体化

发布时间：2024年09月03日

`LLM应用` `硬件设计` `人工智能`

> AIvril: AI-Driven RTL Generation With Verification In-The-Loop

# 摘要

> 大型语言模型 (LLM) 具备执行复杂自然语言处理任务的能力，有望彻底改变硬件设计流程，预测显示前端和后端任务或将很快实现全自动化。目前，LLM 在简化 RTL 生成、提升效率和推动创新方面展现出巨大潜力。然而，其概率特性也使其容易出现不准确性，这在强调可靠性和精度的 RTL 设计中尤为致命。为应对这些挑战，本文推出 AIvril 框架，旨在提升 RTL 感知 LLM 的准确性与可靠性。AIvril 通过多代理、LLM 不可知系统实现自动语法校正与功能验证，大幅减少甚至消除错误代码生成。实验结果显示，相较于以往方法，AIvril 使代码质量提升近一倍，验证目标达成率高达 88.46%。这一突破性进展，不仅推动了硬件设计流程的自动化与优化，更为 AI 驱动的 RTL 设计提供了更为可靠的解决方案。

> Large Language Models (LLMs) are computational models capable of performing complex natural language processing tasks. Leveraging these capabilities, LLMs hold the potential to transform the entire hardware design stack, with predictions suggesting that front-end and back-end tasks could be fully automated in the near future. Currently, LLMs show great promise in streamlining Register Transfer Level (RTL) generation, enhancing efficiency, and accelerating innovation. However, their probabilistic nature makes them prone to inaccuracies - a significant drawback in RTL design, where reliability and precision are essential.
  To address these challenges, this paper introduces AIvril, an advanced framework designed to enhance the accuracy and reliability of RTL-aware LLMs. AIvril employs a multi-agent, LLM-agnostic system for automatic syntax correction and functional verification, significantly reducing - and in many cases, completely eliminating - instances of erroneous code generation. Experimental results conducted on the VerilogEval-Human dataset show that our framework improves code quality by nearly 2x when compared to previous works, while achieving an 88.46% success rate in meeting verification objectives. This represents a critical step toward automating and optimizing hardware design workflows, offering a more dependable methodology for AI-driven RTL design.

[Arxiv](https://arxiv.org/abs/2409.11411)