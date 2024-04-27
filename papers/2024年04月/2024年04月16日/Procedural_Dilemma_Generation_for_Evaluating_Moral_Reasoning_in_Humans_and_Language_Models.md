# 生成程序性道德困境，以评估人类与语言模型的道德推理能力。

发布时间：2024年04月16日

`分类：LLM应用` `AI伦理` `道德评估`

> Procedural Dilemma Generation for Evaluating Moral Reasoning in Humans and Language Models

# 摘要

> 随着语言模型等AI系统在影响人类生活决策中扮演越来越重要的角色，这些系统必须具备坚实的道德推理能力。为此，我们迫切需要建立一套系统的评估机制。我们提出了一个框架，利用语言模型将描述道德困境关键要素的因果图转换成提示模板。通过这一框架，我们生成了一个包含50个场景和400个独特测试项的大规模多样化道德困境集合——OffTheRails基准测试。我们从人类参与者那里收集了对我们测试项子集的道德许可性和意图判断，并将其与两种语言模型（GPT-4和Claude-2）在八种不同情境下的表现进行了对比。研究发现，在伤害作为必要手段而非副作用的道德困境中，无论是参与者还是语言模型，其道德许可性评价较低，而意图评价较高。对于可避免与不可避免的伤害结果，也呈现出类似的趋势。然而，伤害是由行动引起还是由未行动引起，并未产生明显影响。我们讨论了当前提示生成流程的局限，并探讨了如何改进情境设计以提升实验效果的强度。

> As AI systems like language models are increasingly integrated into decision-making processes affecting people's lives, it's critical to ensure that these systems have sound moral reasoning. To test whether they do, we need to develop systematic evaluations. We provide a framework that uses a language model to translate causal graphs that capture key aspects of moral dilemmas into prompt templates. With this framework, we procedurally generated a large and diverse set of moral dilemmas -- the OffTheRails benchmark -- consisting of 50 scenarios and 400 unique test items. We collected moral permissibility and intention judgments from human participants for a subset of our items and compared these judgments to those from two language models (GPT-4 and Claude-2) across eight conditions. We find that moral dilemmas in which the harm is a necessary means (as compared to a side effect) resulted in lower permissibility and higher intention ratings for both participants and language models. The same pattern was observed for evitable versus inevitable harmful outcomes. However, there was no clear effect of whether the harm resulted from an agent's action versus from having omitted to act. We discuss limitations of our prompt generation pipeline and opportunities for improving scenarios to increase the strength of experimental effects.

![生成程序性道德困境，以评估人类与语言模型的道德推理能力。](../../../paper_images/2404.10975/x1.png)

![生成程序性道德困境，以评估人类与语言模型的道德推理能力。](../../../paper_images/2404.10975/x2.png)

![生成程序性道德困境，以评估人类与语言模型的道德推理能力。](../../../paper_images/2404.10975/x3.png)

![生成程序性道德困境，以评估人类与语言模型的道德推理能力。](../../../paper_images/2404.10975/x4.png)

![生成程序性道德困境，以评估人类与语言模型的道德推理能力。](../../../paper_images/2404.10975/x5.png)

[Arxiv](https://arxiv.org/abs/2404.10975)