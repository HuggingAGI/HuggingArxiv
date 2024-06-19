# 大型语言模型助力高效序列决策制定

发布时间：2024年06月17日

`Agent

这篇论文探讨了如何将大型语言模型（LLMs）应用于序列决策领域，并提出了一种新的策略，通过在线模型选择算法高效地将LLMs整合进序列决策过程。这种方法涉及创建一个代理（Agent），该代理能够有效地利用LLMs进行决策，而不需要频繁的梯度更新或大量的LLMs调用。因此，这篇论文的内容与Agent的概念紧密相关，即如何设计和优化一个系统或代理来执行特定的任务，在这种情况下是序列决策。` `序列决策` `机器学习`

> Efficient Sequential Decision Making with Large Language Models

# 摘要

> 本文探讨如何将大型语言模型（LLMs）的优势应用于序列决策领域。目前的方法主要有两种：一是重新训练或微调LLMs以适应决策任务，二是为预训练的LLMs设计特定提示。前者因计算成本高昂而受限，后者效果不佳。为此，我们提出了一种新策略，通过在线模型选择算法，高效地将LLMs整合进序列决策过程。实验证明，我们的方法在统计和计算效率上都显著超越了传统算法和未经优化的LLM代理。具体来说，我们的方法无需频繁的LLMs梯度更新，且在整个决策过程中，LLMs的调用次数大幅减少。例如，在一个大规模的亚马逊数据集上，我们的方法在仅使用LLMs的1.5%时间步内，性能提升了超过6倍。

> This paper focuses on extending the success of large language models (LLMs) to sequential decision making. Existing efforts either (i) re-train or finetune LLMs for decision making, or (ii) design prompts for pretrained LLMs. The former approach suffers from the computational burden of gradient updates, and the latter approach does not show promising results. In this paper, we propose a new approach that leverages online model selection algorithms to efficiently incorporate LLMs agents into sequential decision making. Statistically, our approach significantly outperforms both traditional decision making algorithms and vanilla LLM agents. Computationally, our approach avoids the need for expensive gradient updates of LLMs, and throughout the decision making process, it requires only a small number of LLM calls. We conduct extensive experiments to verify the effectiveness of our proposed approach. As an example, on a large-scale Amazon dataset, our approach achieves more than a $6$x performance gain over baselines while calling LLMs in only $1.5$\% of the time steps.

![大型语言模型助力高效序列决策制定](../../../paper_images/2406.12125/x1.png)

![大型语言模型助力高效序列决策制定](../../../paper_images/2406.12125/x2.png)

![大型语言模型助力高效序列决策制定](../../../paper_images/2406.12125/x3.png)

[Arxiv](https://arxiv.org/abs/2406.12125)