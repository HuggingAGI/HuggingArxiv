# 生成程序性道德困境，以评估人类和语言模型的道德推理能力。

发布时间：2024年04月16日

`分类：LLM应用` `AI伦理` `道德评估`

> Procedural Dilemma Generation for Evaluating Moral Reasoning in Humans and Language Models

# 摘要

> 随着语言模型等AI系统在影响人类生活的决策过程中扮演越来越重要的角色，确保它们具备坚实的道德推理能力变得尤为关键。为此，我们必须开展系统性的评估工作。本研究提出了一种框架，该框架利用语言模型将描述道德困境核心要素的因果图转换为提示模板。基于此框架，我们生成了一套内容丰富、多样化的道德困境数据集——OffTheRails基准测试，共包含50个情境和400个独特的测试案例。我们从人类参与者那里收集了对我们数据子集的道德许可性和意图性判断，并将其与两个语言模型（GPT-4和Claude-2）在八种不同条件下的判断进行了对比分析。研究发现，在伤害是必要手段而非副作用的道德困境中，无论是参与者还是语言模型，其许可性评价都较低，而意图性评价则较高。对于可避免与不可避免的伤害结果，也呈现出类似的趋势。然而，当伤害是由代理的行为引起与未采取行动引起时，并未发现明显的差异。我们讨论了当前提示生成流程的局限性，并提出了改进情景设计以增强实验效应强度的可能途径。

> As AI systems like language models are increasingly integrated into decision-making processes affecting people's lives, it's critical to ensure that these systems have sound moral reasoning. To test whether they do, we need to develop systematic evaluations. We provide a framework that uses a language model to translate causal graphs that capture key aspects of moral dilemmas into prompt templates. With this framework, we procedurally generated a large and diverse set of moral dilemmas -- the OffTheRails benchmark -- consisting of 50 scenarios and 400 unique test items. We collected moral permissibility and intention judgments from human participants for a subset of our items and compared these judgments to those from two language models (GPT-4 and Claude-2) across eight conditions. We find that moral dilemmas in which the harm is a necessary means (as compared to a side effect) resulted in lower permissibility and higher intention ratings for both participants and language models. The same pattern was observed for evitable versus inevitable harmful outcomes. However, there was no clear effect of whether the harm resulted from an agent's action versus from having omitted to act. We discuss limitations of our prompt generation pipeline and opportunities for improving scenarios to increase the strength of experimental effects.

![生成程序性道德困境，以评估人类和语言模型的道德推理能力。](../../../paper_images/2404.10975/x1.png)

![生成程序性道德困境，以评估人类和语言模型的道德推理能力。](../../../paper_images/2404.10975/x2.png)

![生成程序性道德困境，以评估人类和语言模型的道德推理能力。](../../../paper_images/2404.10975/x3.png)

![生成程序性道德困境，以评估人类和语言模型的道德推理能力。](../../../paper_images/2404.10975/x4.png)

![生成程序性道德困境，以评估人类和语言模型的道德推理能力。](../../../paper_images/2404.10975/x5.png)

[Arxiv](https://arxiv.org/abs/2404.10975)