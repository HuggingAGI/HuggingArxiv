# 通过游戏化众包获取高质量数据，助力视觉模型的微调

发布时间：2024年10月05日

`LLM应用` `人工智能` `游戏化`

> Gamified crowd-sourcing of high-quality data for visual fine-tuning

# 摘要

> 本文提出 Gamified Adversarial Prompting (GAP)，一个通过游戏化方式为大型多模态模型收集高质量数据的新框架。GAP 将数据收集变成一场有趣的游戏，激励玩家提供细致且具有挑战性的问答，以填补模型知识的空白。我们的贡献包括：（1）一种直接针对模型知识弱点收集问答对的方法；（2）一种评估并奖励高质量提交的方法；（3）一个可扩展的游戏化平台，在几周内从超过 50,000 名参与者中成功收集数据。GAP 显著提升了小型多模态模型 MiniCPM-Llama3-V-2.5-8B 的准确性，使其 GPT 分数从 0.147 提升至 0.477，接近 GPT-4V 的基准。此外，GAP 生成的数据不仅提升了 MiniCPM-Llama3-V-2.5-8B 在其他基准上的表现，还对 QWEN2-VL-2B 和 QWEN2-VL-7B 等其他模型产生了积极影响。

> This paper introduces Gamified Adversarial Prompting (GAP), a framework that crowd-sources high-quality data for visual instruction tuning of large multimodal models. GAP transforms the data collection process into an engaging game, incentivizing players to provide fine-grained, challenging questions and answers that target gaps in the model's knowledge. Our contributions include (1) an approach to capture question-answer pairs from humans that directly address weaknesses in a model's knowledge, (2) a method for evaluating and rewarding players that successfully incentivizes them to provide high-quality submissions, and (3) a scalable, gamified platform that succeeds in collecting this data from over 50,000 participants in just a few weeks. Our implementation of GAP has significantly improved the accuracy of a small multimodal model, namely MiniCPM-Llama3-V-2.5-8B, increasing its GPT score from 0.147 to 0.477 on our dataset, approaching the benchmark set by the much larger GPT-4V. Moreover, we demonstrate that the data generated using MiniCPM-Llama3-V-2.5-8B also enhances its performance across other benchmarks, and exhibits cross-model benefits. Specifically, the same data improves the performance of QWEN2-VL-2B and QWEN2-VL-7B on the same multiple benchmarks.

[Arxiv](https://arxiv.org/abs/2410.04038)