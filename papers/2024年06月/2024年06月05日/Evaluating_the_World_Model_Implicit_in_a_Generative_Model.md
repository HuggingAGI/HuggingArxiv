# 探究生成模型内含的世界模型之评估

发布时间：2024年06月05日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）可能暗中掌握的世界模型，并提出了一个正式的评估框架。它通过设计新的评估指标来揭示这些模型的内在结构，并分析了这些模型在特定任务上的表现。这些内容主要关注LLM的理论层面，特别是关于模型理解和评估的问题，因此属于LLM理论分类。` `人工智能` `逻辑推理`

> Evaluating the World Model Implicit in a Generative Model

# 摘要

> 最新研究表明，大型语言模型可能暗中掌握了世界模型。如何评估这一可能性？我们针对由确定性有限自动机支配的现实情况，提出了这一问题的正式框架。这涵盖了从逻辑推理、地理导航、游戏策略到化学等多个领域。我们借鉴语言学中的Myhill-Nerode定理，设计了新的评估指标，用以揭示世界模型的内在结构。通过游戏、逻辑谜题和导航三个实例，我们展示了这些指标的效用。尽管这些生成模型在传统评估中表现出色，但我们的新指标揭示了它们的世界模型实际上缺乏连贯性。这种不连贯性使得模型在面对细微不同的任务时显得脆弱。构建能够深刻理解其领域逻辑的生成模型极具价值；我们的研究为此提供了新的评估途径。

> Recent work suggests that large language models may implicitly learn world models. How should we assess this possibility? We formalize this question for the case where the underlying reality is governed by a deterministic finite automaton. This includes problems as diverse as simple logical reasoning, geographic navigation, game-playing, and chemistry. We propose new evaluation metrics for world model recovery inspired by the classic Myhill-Nerode theorem from language theory. We illustrate their utility in three domains: game playing, logic puzzles, and navigation. In all domains, the generative models we consider do well on existing diagnostics for assessing world models, but our evaluation metrics reveal their world models to be far less coherent than they appear. Such incoherence creates fragility: using a generative model to solve related but subtly different tasks can lead it to fail badly. Building generative models that meaningfully capture the underlying logic of the domains they model would be immensely valuable; our results suggest new ways to assess how close a given model is to that goal.

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x1.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x2.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr0.2.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x3.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x4.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x5.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist0.5_randerr0.25.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist0.5_randerr0.25.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist1.0_randerr0.25.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg4_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist1.0_randerr0.25.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/shortest_seq100000_deg8_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist0.5_randerr0.35.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist0.5_randerr0.35.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist1.0_randerr0.35.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg4_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist1.0_randerr0.35.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/traffic_seq100000_deg8_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr0.2.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist0.5_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist0.5_randerr0.2.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist0.5_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist1.0_randerr0.2.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg4_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist1.0_randerr0.0.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist1.0_randerr0.2.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/random_seq100000_deg8_dist1.0_randerr-1.jpg)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x6.png)

![探究生成模型内含的世界模型之评估](../../../paper_images/2406.03689/x7.png)

[Arxiv](https://arxiv.org/abs/2406.03689)