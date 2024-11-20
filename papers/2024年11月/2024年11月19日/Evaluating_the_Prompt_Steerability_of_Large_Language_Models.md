# 对大型语言模型的提示可操纵性进行评估

发布时间：2024年11月19日

`LLM应用` `人工智能` `模型评估`

> Evaluating the Prompt Steerability of Large Language Models

# 摘要

> 构建多元的人工智能，得设计能被塑造从而代表众多价值体系和文化的模型。要达成此目标，首先得能评估给定模型反映各类角色的能力程度。为此，我们提出了一个以提示为函数来评估模型角色可操控性的基准。我们的设计基于提示可操控性的正式定义，它分析了模型的联合行为分布能从基线行为转变的程度。通过定义可操控性指标，并查看这些指标如何随操控努力而变化，我们能够估量模型在各种角色维度和方向上的可操控性。我们的基准显示，当前许多模型的可操控性有限——这源于它们基线行为的偏差以及在众多角色维度上可操控性的不对称。我们在 https://github.com/IBM/prompt-steering 公布了我们基准的实现。

> Building pluralistic AI requires designing models that are able to be shaped to represent a wide range of value systems and cultures. Achieving this requires first being able to evaluate the degree to which a given model is capable of reflecting various personas. To this end, we propose a benchmark for evaluating the steerability of model personas as a function of prompting. Our design is based on a formal definition of prompt steerability, which analyzes the degree to which a model's joint behavioral distribution can be shifted from its baseline behavior. By defining steerability indices and inspecting how these indices change as a function of steering effort, we can estimate the steerability of a model across various persona dimensions and directions. Our benchmark reveals that the steerability of many current models is limited -- due to both a skew in their baseline behavior and an asymmetry in their steerability across many persona dimensions. We release an implementation of our benchmark at https://github.com/IBM/prompt-steering.

[Arxiv](https://arxiv.org/abs/2411.12405)