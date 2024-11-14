# 动态奖励与提示优化能够实现语言模型的免调整自对齐

发布时间：2024年11月13日

`LLM应用` `语言模型` `人工智能`

> Dynamic Rewarding with Prompt Optimization Enables Tuning-free Self-Alignment of Language Models

# 摘要

> 使大型语言模型（LLMs）对齐传统上依赖于昂贵的训练和人类偏好注释。自我对齐旨在通过使模型能够自我对齐来降低这些费用。为了进一步降低成本并在没有任何昂贵的调整或注释的情况下实现对齐，我们引入了一种新的无调整自我对齐方法，即具有提示优化的动态奖励（\ours）。我们的方法利用了基于搜索的优化框架，该框架允许 LLMs 迭代地自我改进并制定最佳对齐指令，所有这些都无需额外的训练或人工干预。\ours 的核心是一种动态奖励机制，它识别并纠正特定于模型的对齐弱点，使 LLMs 能够有效地适应各种对齐挑战。对八个最近的 LLMs（包括开源和闭源）的实证评估表明，\ours 显著提高了对齐性能，基础模型优于其 SFT/RLHF 调整的对应模型。此外，由 \ours 自动优化的提示超过了由人类专家策划的提示，进一步验证了我们方法的有效性。我们的研究结果突出了当前 LLMs 通过推理时间优化实现自适应自我对齐的巨大潜力，补充了基于调整的对齐方法。

> Aligning Large Language Models (LLMs) traditionally relies on costly training and human preference annotations. Self-alignment seeks to reduce these expenses by enabling models to align themselves. To further lower costs and achieve alignment without any expensive tuning or annotations, we introduce a new tuning-free approach for self-alignment, Dynamic Rewarding with Prompt Optimization (\ours). Our approach leverages a search-based optimization framework that allows LLMs to iteratively self-improve and craft the optimal alignment instructions, all without additional training or human intervention. The core of \ours is a dynamic rewarding mechanism, which identifies and rectifies model-specific alignment weaknesses, allowing LLMs to adapt efficiently to diverse alignment challenges. Empirical evaluations on eight recent LLMs, both open- and closed-sourced, demonstrate that \ours significantly enhances alignment performance, with base models outperforming their SFT/RLHF-tuned counterparts. Moreover, the prompts automatically optimized by \ours surpass those curated by human experts, further validating the effectiveness of our approach. Our findings highlight the great potential of current LLMs to achieve adaptive self-alignment through inference-time optimization, complementing tuning-based alignment methods.

[Arxiv](https://arxiv.org/abs/2411.08733)