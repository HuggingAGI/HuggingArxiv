# S$^3$c-Math：通过自发的步骤级自我修正，大型语言模型在数学推理方面表现更佳。

发布时间：2024年09月02日

`LLM应用` `人工智能`

> S$^3$c-Math: Spontaneous Step-level Self-correction Makes Large Language Models Better Mathematical Reasoners

# 摘要

> 自我纠正是激发大型语言模型（LLMs）推理潜能的创新方法，它能在推理过程中自动检测并修正错误。然而，现有研究并未将此视为LLMs的内在能力，而是依赖事后生成、外部知识等手段实现修正。本文中，我们提出S$^3$c-Math系列模型，能在数学推理中自发进行步骤级自我纠错，提升推理的准确性。我们采用步骤级采样构建数据，并设计训练策略，使LLMs具备此能力。实验证明，我们的方法在GSM8K、MATH等基准测试中表现卓越。据我们所知，这是首次在数学推理领域引入LLMs的自发步骤级自我纠错能力。

> Self-correction is a novel method that can stimulate the potential reasoning abilities of large language models (LLMs). It involves detecting and correcting errors during the inference process when LLMs solve reasoning problems. However, recent works do not regard self-correction as a spontaneous and intrinsic capability of LLMs. Instead, such correction is achieved through post-hoc generation, external knowledge introduction, multi-model collaboration, and similar techniques. In this paper, we propose a series of mathematical LLMs called S$^3$c-Math, which are able to perform Spontaneous Step-level Self-correction for Mathematical reasoning. This capability helps LLMs to recognize whether their ongoing inference tends to contain errors and simultaneously correct these errors to produce a more reliable response. We proposed a method, which employs a step-level sampling approach to construct step-wise self-correction data for achieving such ability. Additionally, we implement a training strategy that uses above constructed data to equip LLMs with spontaneous step-level self-correction capacities. Our data and methods have been demonstrated to be effective across various foundation LLMs, consistently showing significant progress in evaluations on GSM8K, MATH, and other mathematical benchmarks. To the best of our knowledge, we are the first to introduce the spontaneous step-level self-correction ability of LLMs in mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2409.01524)