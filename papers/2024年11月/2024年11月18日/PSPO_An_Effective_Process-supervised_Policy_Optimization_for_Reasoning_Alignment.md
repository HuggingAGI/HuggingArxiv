# PSPO*：用于推理对齐的高效过程监督策略优化

发布时间：2024年11月18日

`LLM应用`

> PSPO*: An Effective Process-supervised Policy Optimization for Reasoning Alignment

# 摘要

> 过程监督能在思维链推理的每一步给予反馈，从而提升大型语言模型在推理任务中的表现。但因缺乏有效的过程监督手段，就算是先进的大型语言模型也容易产生逻辑错误和冗余推理。我们指出，过程监督的成效很大程度取决于推理链的准确度和长度。而且，我们发现这些因素与推理过程的总体奖励分数呈非线性关系。受此启发，我们提出了全新的过程监督范式PSPO*，它系统地规划了从奖励模型训练到策略优化的工作流程，突出了非线性奖励在过程监督中的重要性。基于PSPO*，我们开发了PSPO-WRS，其在确定奖励分数时考虑了推理步骤的数量，并采用调整后的威布尔分布进行非线性奖励塑造。在六个数学推理数据集上的实验结果显示，PSPO-WRS一直优于当下的主流模型。

> Process supervision enhances the performance of large language models in reasoning tasks by providing feedback at each step of chain-of-thought reasoning. However, due to the lack of effective process supervision methods, even advanced large language models are prone to logical errors and redundant reasoning. We claim that the effectiveness of process supervision significantly depends on both the accuracy and the length of reasoning chains. Moreover, we identify that these factors exhibit a nonlinear relationship with the overall reward score of the reasoning process. Inspired by these insights, we propose a novel process supervision paradigm, PSPO*, which systematically outlines the workflow from reward model training to policy optimization, and highlights the importance of nonlinear rewards in process supervision. Based on PSPO*, we develop the PSPO-WRS, which considers the number of reasoning steps in determining reward scores and utilizes an adjusted Weibull distribution for nonlinear reward shaping. Experimental results on six mathematical reasoning datasets demonstrate that PSPO-WRS consistently outperforms current mainstream models.

[Arxiv](https://arxiv.org/abs/2411.11681)