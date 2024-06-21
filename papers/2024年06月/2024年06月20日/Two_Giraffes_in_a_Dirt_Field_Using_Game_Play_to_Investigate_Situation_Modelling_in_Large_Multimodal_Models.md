# 《尘土中的长颈鹿：通过游戏探索大型多模态模型中的情境构建》

发布时间：2024年06月20日

`Agent

理由：这篇论文探讨的是多模态模型的评估方法，特别是通过设计目标导向的游戏来自我玩耍的方式进行评估。这种方法涉及到模型的自主行为和决策过程，类似于Agent的行为模式，即模型需要根据视觉信息和对话情境做出反应和表达。因此，这篇论文更符合Agent分类，因为它关注的是模型如何作为一个智能体在特定环境中进行交互和表现。` `多模态学习` `游戏开发`

> Two Giraffes in a Dirt Field: Using Game Play to Investigate Situation Modelling in Large Multimodal Models

# 摘要

> 尽管纯文本模型的评估已有所进步，但多模态（文本与图像结合）模型的发展似乎再次超越了评估方法的进步。本文引入了一种新颖的评估方式——通过目标导向的游戏自我玩耍，为多模态模型评估增添了新维度，与传统的基于参考和偏好的评估相辅相成。我们设计了一系列游戏，旨在考验模型从视觉信息中提取并对话中表达情境的能力。实验显示，顶尖的封闭模型在这些游戏中表现出色，而开放权重模型则面临挑战。深入分析揭示，这些顶尖模型强大的深度描述能力是其成功的关键。尽管如此，两种模型都还有进步，这使得我们的评估基准依然具有重要意义。

> While the situation has improved for text-only models, it again seems to be the case currently that multimodal (text and image) models develop faster than ways to evaluate them. In this paper, we bring a recently developed evaluation paradigm from text models to multimodal models, namely evaluation through the goal-oriented game (self) play, complementing reference-based and preference-based evaluation. Specifically, we define games that challenge a model's capability to represent a situation from visual information and align such representations through dialogue. We find that the largest closed models perform rather well on the games that we define, while even the best open-weight models struggle with them. On further analysis, we find that the exceptional deep captioning capabilities of the largest models drive some of the performance. There is still room to grow for both kinds of models, ensuring the continued relevance of the benchmark.

[Arxiv](https://arxiv.org/abs/2406.14035)