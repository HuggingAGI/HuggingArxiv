# 在预训练中，程序性知识驱动着大型语言模型进行推理

发布时间：2024年11月19日

`LLM理论` `语言模型`

> Procedural Knowledge in Pretraining Drives Reasoning in Large Language Models

# 摘要

> 近年来，大型语言模型的能力与局限已被极为详尽地描绘出来，呈现出一幅既有趣又矛盾的图景。一方面，大型语言模型展现出解决问题的普遍能力；另一方面，和人类相比，它们暴露出惊人的推理差距，令人对其泛化策略的稳健性产生质疑。由于大型语言模型设计中使用的数据量庞大，我们无法采用传统衡量泛化的方法——训练-测试集分离。为了克服这一难题，我们通过探究大型语言模型所依赖的预训练数据，来研究它们在执行推理任务时运用的泛化策略。针对两个不同规模的模型（70 亿和 350 亿）以及 25 亿的预训练标记，我们明确了哪些文档会影响三个简单数学推理任务的模型输出，并将其与回答事实性问题的有影响力数据进行对比。我们发现，虽然模型针对每个事实性问题大多依赖不同的数据集，但在同一任务的不同推理问题中，一份文档往往有着相似的影响力，这表明存在程序性知识。我们还进一步发现，事实性问题的答案常常出现在最具影响力的数据中。然而，对于推理问题，答案通常影响力不大，中间推理步骤的答案亦是如此。当我们对推理问题的顶级文档进行定性描述时，我们确认有影响力的文档通常包含程序性知识，比如展示如何通过公式或代码获取解决方案。我们的研究结果表明，模型的推理方式不像检索，更像是一种从进行类似推理的文档中综合程序性知识的可泛化策略。

> The capabilities and limitations of Large Language Models have been sketched out in great detail in recent years, providing an intriguing yet conflicting picture. On the one hand, LLMs demonstrate a general ability to solve problems. On the other hand, they show surprising reasoning gaps when compared to humans, casting doubt on the robustness of their generalisation strategies. The sheer volume of data used in the design of LLMs has precluded us from applying the method traditionally used to measure generalisation: train-test set separation. To overcome this, we study what kind of generalisation strategies LLMs employ when performing reasoning tasks by investigating the pretraining data they rely on. For two models of different sizes (7B and 35B) and 2.5B of their pretraining tokens, we identify what documents influence the model outputs for three simple mathematical reasoning tasks and contrast this to the data that are influential for answering factual questions. We find that, while the models rely on mostly distinct sets of data for each factual question, a document often has a similar influence across different reasoning questions within the same task, indicating the presence of procedural knowledge. We further find that the answers to factual questions often show up in the most influential data. However, for reasoning questions the answers usually do not show up as highly influential, nor do the answers to the intermediate reasoning steps. When we characterise the top ranked documents for the reasoning questions qualitatively, we confirm that the influential documents often contain procedural knowledge, like demonstrating how to obtain a solution using formulae or code. Our findings indicate that the approach to reasoning the models use is unlike retrieval, and more like a generalisable strategy that synthesises procedural knowledge from documents doing a similar form of reasoning.

[Arxiv](https://arxiv.org/abs/2411.12580)