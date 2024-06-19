# 大型语言模型在序列决策制定中的高效应用

发布时间：2024年06月17日

`Agent

这篇论文探讨了如何将大型语言模型（LLMs）应用于序列决策领域，并提出了一种创新的方法，通过在线模型选择算法高效地将LLMs融入序列决策过程。这种方法可以被视为一种智能代理（Agent），因为它能够自主地进行决策，并在序列决策任务中优化使用LLMs。因此，这篇论文适合归类到Agent分类中。` `序列决策` `人工智能`

> Efficient Sequential Decision Making with Large Language Models

# 摘要

> 本文探讨如何将大型语言模型（LLMs）的强大能力应用于序列决策领域。目前的方法主要有两种：一是重新训练或微调LLMs以适应决策任务，二是为预训练的LLMs设计特定提示。前者因计算成本高昂而受限，后者则效果不佳。为此，我们提出了一种创新方法，通过在线模型选择算法，高效地将LLMs融入序列决策过程。统计结果显示，我们的方法不仅超越了传统决策算法，也优于未经优化的LLM代理。在计算效率上，我们的方法避免了LLMs昂贵的梯度更新，整个决策过程中仅需少量LLM调用。通过广泛的实验验证，我们的方法在实际应用中表现出色。以亚马逊大型数据集为例，我们的方法在仅使用LLMs 1.5%的时间步内，性能提升了超过6倍。

> This paper focuses on extending the success of large language models (LLMs) to sequential decision making. Existing efforts either (i) re-train or finetune LLMs for decision making, or (ii) design prompts for pretrained LLMs. The former approach suffers from the computational burden of gradient updates, and the latter approach does not show promising results. In this paper, we propose a new approach that leverages online model selection algorithms to efficiently incorporate LLMs agents into sequential decision making. Statistically, our approach significantly outperforms both traditional decision making algorithms and vanilla LLM agents. Computationally, our approach avoids the need for expensive gradient updates of LLMs, and throughout the decision making process, it requires only a small number of LLM calls. We conduct extensive experiments to verify the effectiveness of our proposed approach. As an example, on a large-scale Amazon dataset, our approach achieves more than a $6$x performance gain over baselines while calling LLMs in only $1.5$\% of the time steps.

![大型语言模型在序列决策制定中的高效应用](../../../paper_images/2406.12125/x1.png)

![大型语言模型在序列决策制定中的高效应用](../../../paper_images/2406.12125/x2.png)

![大型语言模型在序列决策制定中的高效应用](../../../paper_images/2406.12125/x3.png)

[Arxiv](https://arxiv.org/abs/2406.12125)