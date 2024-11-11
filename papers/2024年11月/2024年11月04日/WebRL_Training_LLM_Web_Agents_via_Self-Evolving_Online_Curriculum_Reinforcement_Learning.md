# WebRL：通过自进化在线课程强化学习训练大型语言模型网络代理

发布时间：2024年11月04日

`Agent`

> WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning

# 摘要

> 大型语言模型（LLM）作为自主代理显示出了显著的潜力，特别是在基于网络的任务中。然而，现有的 LLM 网络代理严重依赖昂贵的专有 LLM API，而开放的 LLM 缺乏必要的决策能力。本文介绍了 WebRL，这是一个自我进化的在线课程强化学习框架，旨在使用开放的 LLM 训练高性能的网络代理。WebRL 解决了构建 LLM 网络代理的三个关键挑战，包括训练任务的稀缺、稀疏的反馈信号和在线学习中的策略分布漂移。具体来说，WebRL 包含 1）一个从失败尝试中生成新任务的自我进化课程，2）一个强大的结果监督奖励模型（ORM），以及 3）自适应强化学习策略以确保持续改进。我们应用 WebRL 将开放的 Llama-3.1 和 GLM-4 模型转变为熟练的网络代理。在 WebArena-Lite 上，WebRL 将 Llama-3.1-8B 的成功率从 4.8％提高到 42.4％，将 GLM-4-9B 的成功率从 6.1％提高到 43％。这些开放模型显著超过了 GPT-4-Turbo（17.6％）和 GPT-4o（13.9％）的性能，并优于之前在开放 LLM 上训练的最先进的网络代理（AutoWebGLM，18.2％）。我们的研究结果表明 WebRL 在弥合开放和专有基于 LLM 的网络代理之间的差距方面的有效性，为更易访问和强大的自主网络交互系统铺平了道路。

> Large language models (LLMs) have shown remarkable potential as autonomous agents, particularly in web-based tasks. However, existing LLM web agents heavily rely on expensive proprietary LLM APIs, while open LLMs lack the necessary decision-making capabilities. This paper introduces WebRL, a self-evolving online curriculum reinforcement learning framework designed to train high-performance web agents using open LLMs. WebRL addresses three key challenges in building LLM web agents, including the scarcity of training tasks, sparse feedback signals, and policy distribution drift in online learning. Specifically, WebRL incorporates 1) a self-evolving curriculum that generates new tasks from unsuccessful attempts, 2) a robust outcome-supervised reward model (ORM), and 3) adaptive reinforcement learning strategies to ensure consistent improvements. We apply WebRL to transform open Llama-3.1 and GLM-4 models into proficient web agents. On WebArena-Lite, WebRL improves the success rate of Llama-3.1-8B from 4.8% to 42.4%, and from 6.1% to 43% for GLM-4-9B. These open models significantly surpass the performance of GPT-4-Turbo (17.6%) and GPT-4o (13.9%) and outperform previous state-of-the-art web agents trained on open LLMs (AutoWebGLM, 18.2%). Our findings demonstrate WebRL's effectiveness in bridging the gap between open and proprietary LLM-based web agents, paving the way for more accessible and powerful autonomous web interaction systems.

[Arxiv](https://arxiv.org/abs/2411.02337)