# 关于大型语言模型高效问答的动态策略规划

发布时间：2024年10月30日

`LLM应用` `语言模型`

> Dynamic Strategy Planning for Efficient Question Answering with Large Language Models

# 摘要

> 研究显示，像推理（比如思维链）、规划（比如 SelfAsk）以及检索增强生成策略等，能有效提升大型语言模型（LLMs）在诸如问答等各类任务中的表现。但用单一固定策略去回答不同类型的问题，不仅性能欠佳，在生成的输出标记和执行的检索方面也效率不高。在我们的工作里，我们提出了一种新颖的技术 DyPlan，为 LLMs 引入动态策略选择流程，以提升问答表现并降低成本。DyPlan 包含一个初始决策步骤，依据输入问题选择最适宜的策略，并相应引导 LLM 的响应生成。我们把 DyPlan 拓展为 DyPlan-verify，增添了内部验证和纠正流程，进一步丰富生成的答案。在三个知名的多跳问答（MHQA）数据集上的实验表明，相较于最佳基线模型，DyPlan 能将模型性能提高 7 - 13％，同时把成本降低 11 - 32％。

> Research has shown the effectiveness of reasoning (e.g., Chain-of-Thought), planning (e.g., SelfAsk), and retrieval augmented generation strategies to improve the performance of Large Language Models (LLMs) on various tasks, such as question answering. However, using a single fixed strategy to answer different kinds of questions is suboptimal in performance and inefficient in terms of generated output tokens and performed retrievals. In our work, we propose a novel technique DyPlan, to induce a dynamic strategy selection process in LLMs, to improve performance and reduce costs in question-answering. DyPlan incorporates an initial decision step to select the most suitable strategy conditioned on the input question and guides the LLM's response generation accordingly. We extend DyPlan to DyPlan-verify, adding an internal verification and correction process to further enrich the generated answer. Experiments on three prominent multi-hop question answering (MHQA) datasets reveal how DyPlan can improve model performance by 7-13% while reducing the cost by 11-32% relative to the best baseline model.

[Arxiv](https://arxiv.org/abs/2410.23511)