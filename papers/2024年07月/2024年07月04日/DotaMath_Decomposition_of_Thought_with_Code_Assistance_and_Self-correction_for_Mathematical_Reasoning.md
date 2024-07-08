# DotaMath：借助代码辅助与自我修正，实现数学推理思维的精细分解

发布时间：2024年07月04日

`LLM应用`

> DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning

# 摘要

> 大型语言模型（LLM）在简单数学问题上取得了显著进步，但在处理更复杂、更具挑战性的数学任务时仍显不足。本文介绍了一种名为 DotaMath 的 LLM 系列，通过代码辅助和自我修正的思维分解方法，将复杂数学任务分解为简单逻辑子任务，利用代码解决，并进行自我反思和修正。我们通过注释多样化的工具使用轨迹，在 GSM8K 和 MATH 数据集上生成包含 574K 查询-响应对的 DotaMathQA 数据集，并使用模仿学习训练 LLM。DotaMath 模型在各类基准测试中表现卓越，特别是在 MATH 数据集上达到 64.8%，在 GSM8K 上达到 86.7%，平均竞争力为 80.1%。我们期待 DotaMath 范式为解决复杂数学问题开辟新途径，相关代码已公开发布。

> Large language models (LLMs) have made impressive progress in handling simple math problems, yet they still struggle with more challenging and complex mathematical tasks. In this paper, we introduce a series of LLMs that employs the Decomposition of thought with code assistance and self-correction for mathematical reasoning, dubbed as DotaMath. DotaMath models tackle complex mathematical tasks by decomposing them into simpler logical subtasks, leveraging code to solve these subtasks, obtaining fine-grained feedback from the code interpreter, and engaging in self-reflection and correction. By annotating diverse interactive tool-use trajectories and employing query evolution on GSM8K and MATH datasets, we generate an instruction fine-tuning dataset called DotaMathQA with 574K query-response pairs. We train a series of base LLMs using imitation learning on DotaMathQA, resulting in DotaMath models that achieve remarkable performance compared to open-source LLMs across various in-domain and out-of-domain benchmarks. Notably, DotaMath-deepseek-7B showcases an outstanding performance of 64.8% on the competitive MATH dataset and 86.7% on GSM8K. Besides, DotaMath-deepseek-7B maintains strong competitiveness on a series of in-domain and out-of-domain benchmarks (Avg. 80.1%). Looking forward, we anticipate that the DotaMath paradigm will open new pathways for addressing intricate mathematical problems. Our code is publicly available at https://github.com/ChengpengLi1003/DotaMath.

[Arxiv](https://arxiv.org/abs/2407.04078)