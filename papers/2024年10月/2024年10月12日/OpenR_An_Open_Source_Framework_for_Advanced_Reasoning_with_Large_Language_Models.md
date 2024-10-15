# OpenR：专为大型语言模型高级推理设计的开源框架

发布时间：2024年10月12日

`LLM应用` `人工智能` `开源软件`

> OpenR: An Open Source Framework for Advanced Reasoning with Large Language Models

# 摘要

> 本报告介绍了 OpenR，一个开源框架，旨在整合关键组件以提升 LLM 的推理能力。OpenR 集成了数据获取、强化学习训练（在线和离线）以及非自回归解码，形成一个连贯的软件平台。我们的目标是建立一个开源平台和社区，以加速 LLM 推理的发展。受 OpenAI 的 o1 模型启发，OpenR 整合了测试时计算、强化学习和过程监督，以提升 LLM 的推理能力。我们的工作首次提供了一个开源框架，探索了 OpenAI 的 o1 模型的核心技术与强化学习，实现了超越传统自回归方法的高级推理能力。我们通过在 MATH 数据集上评估 OpenR，展示了其有效性。初步实验证实了显著的收益，推理和性能的相对改进由测试时计算和通过过程奖励模型进行的强化学习驱动。OpenR 框架，包括代码、模型和数据集，可在 https://openreasoner.github.io 访问。

> In this technical report, we introduce OpenR, an open-source framework designed to integrate key components for enhancing the reasoning capabilities of large language models (LLMs). OpenR unifies data acquisition, reinforcement learning training (both online and offline), and non-autoregressive decoding into a cohesive software platform. Our goal is to establish an open-source platform and community to accelerate the development of LLM reasoning. Inspired by the success of OpenAI's o1 model, which demonstrated improved reasoning abilities through step-by-step reasoning and reinforcement learning, OpenR integrates test-time compute, reinforcement learning, and process supervision to improve reasoning in LLMs. Our work is the first to provide an open-source framework that explores the core techniques of OpenAI's o1 model with reinforcement learning, achieving advanced reasoning capabilities beyond traditional autoregressive methods. We demonstrate the efficacy of OpenR by evaluating it on the MATH dataset, utilising publicly available data and search methods. Our initial experiments confirm substantial gains, with relative improvements in reasoning and performance driven by test-time computation and reinforcement learning through process reward models. The OpenR framework, including code, models, and datasets, is accessible at https://openreasoner.github.io.

[Arxiv](https://arxiv.org/abs/2410.09671)