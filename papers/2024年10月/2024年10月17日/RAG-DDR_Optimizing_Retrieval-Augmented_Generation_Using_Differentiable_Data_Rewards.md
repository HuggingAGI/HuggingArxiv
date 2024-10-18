# RAG-DDR：通过可微数据奖励优化检索增强生成

发布时间：2024年10月17日

`RAG` `人工智能`

> RAG-DDR: Optimizing Retrieval-Augmented Generation Using Differentiable Data Rewards

# 摘要

> RAG 通过从外部资源检索知识，有效减少了 LLM 中的幻觉。为使 LLM 适应 RAG 流程，现有方法通过指令调优优化 LLM，提升其利用检索知识的能力。然而，这种监督微调方法使 RAG 模块过度拟合训练信号，忽略了 RAG 系统中不同代理的数据偏好差异。本文提出可微分数据奖励 (DDR) 方法，通过调整 RAG 模块间的数据偏好，端到端训练 RAG 系统。DDR 通过回滚方法收集奖励，优化每个代理，提示代理采样潜在响应作为扰动，评估其对 RAG 系统的影响，并优化代理以提升系统性能。实验表明，DDR 显著优于 SFT 方法，尤其适用于依赖检索知识的小规模参数 LLM。此外，DDR 能更有效地调整 RAG 模块间的数据偏好，使生成模块在提取关键信息和减少参数记忆与外部知识冲突方面更有效。所有代码可在 https://github.com/OpenMatch/RAG-DDR 获取。

> Retrieval-Augmented Generation (RAG) has proven its effectiveness in mitigating hallucinations in Large Language Models (LLMs) by retrieving knowledge from external resources. To adapt LLMs for RAG pipelines, current approaches use instruction tuning to optimize LLMs, improving their ability to utilize retrieved knowledge. This supervised fine-tuning (SFT) approach focuses on equipping LLMs to handle diverse RAG tasks using different instructions. However, it trains RAG modules to overfit training signals and overlooks the varying data preferences among agents within the RAG system. In this paper, we propose a Differentiable Data Rewards (DDR) method, which end-to-end trains RAG systems by aligning data preferences between different RAG modules. DDR works by collecting the rewards to optimize each agent with a rollout method. This method prompts agents to sample some potential responses as perturbations, evaluates the impact of these perturbations on the whole RAG system, and subsequently optimizes the agent to produce outputs that improve the performance of the RAG system. Our experiments on various knowledge-intensive tasks demonstrate that DDR significantly outperforms the SFT method, particularly for LLMs with smaller-scale parameters that depend more on the retrieved knowledge. Additionally, DDR exhibits a stronger capability to align the data preference between RAG modules. The DDR method makes generation module more effective in extracting key information from documents and mitigating conflicts between parametric memory and external knowledge. All codes are available at https://github.com/OpenMatch/RAG-DDR.

[Arxiv](https://arxiv.org/abs/2410.13509)