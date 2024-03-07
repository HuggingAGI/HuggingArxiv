# [本文探讨通过选择性剪枝技术深入剖析并“卸载”语言模型中的特定知识，实现机器的“忘却”过程。](https://arxiv.org/abs/2403.01267)

> Dissecting Language Models: Machine Unlearning via Selective Pruning

发布时间：2024年03月02日

> 随着LLMs应用的威力增强且普及率提升，掌握并引导其行为显得越发关键。本篇论文引入一种专为LLMs设计的机器剔除学习法。我们创新性地提出了一个针对LLMs的选择性修剪策略，根据神经元在特定功能上相对于整体网络表现的重要性来移除相应神经元，这为高效识别并移除触发特定行为的神经元提供了一种节约计算资源和数据的方法。研究成果揭示了LLMs中无论是前馈还是注意力神经元都具备专业化特性，即在特定任务上，某些神经元较之其他神经元更为关键。

> Understanding and shaping the behaviour of Large Language Models (LLMs) is increasingly important as applications become more powerful and more frequently adopted. This paper introduces a machine unlearning method specifically designed for LLMs. We introduce a selective pruning method for LLMs that removes neurons based on their relative importance on a targeted capability compared to overall network performance. This approach is a compute- and data-efficient method for identifying and removing neurons that enable specific behaviours. Our findings reveal that both feed-forward and attention neurons in LLMs are specialized; that is, for specific tasks, certain neurons are more crucial than others.

`LLM理论`