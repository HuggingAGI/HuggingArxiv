# 哪些因素会影响多模态的上下文学习？深度探究

发布时间：2024年10月27日

`LLM应用` `多模态` `上下文学习`

> What Factors Affect Multi-Modal In-Context Learning? An In-Depth Exploration

# 摘要

> 近来，多模态上下文学习（MM-ICL）发展迅猛，成绩斐然，能在各类任务中表现出色，且无需额外调整参数。然而，MM-ICL 生效的内在规律尚未被充分挖掘。为了弥补这一不足，本研究致力于探讨这样一个问题：“哪些因素会影响 MM-ICL 的性能？”为此，我们运用 6 个视觉大型语言模型和 20 种策略，针对 MM-ICL 的三个核心步骤，即演示检索、演示排序和提示构建，展开了大量实验。我们的研究结果表明：（1）演示检索需要多模态检索器；（2）演示内排序比演示间排序更重要；（3）提示中的介绍性说明有助于增强对任务的理解。我们期望本研究能为未来优化 MM-ICL 策略提供基础性指导。

> Recently, rapid advancements in Multi-Modal In-Context Learning (MM-ICL) have achieved notable success, which is capable of achieving superior performance across various tasks without requiring additional parameter tuning. However, the underlying rules for the effectiveness of MM-ICL remain under-explored. To fill this gap, this work aims to investigate the research question: "What factors affect the performance of MM-ICL?'' To this end, we investigate extensive experiments on the three core steps of MM-ICL including demonstration retrieval, demonstration ordering, and prompt construction using 6 vision large language models and 20 strategies. Our findings highlight (1) the necessity of a multi-modal retriever for demonstration retrieval, (2) the importance of intra-demonstration ordering over inter-demonstration ordering, and (3) the enhancement of task comprehension through introductory instructions in prompts. We hope this study can serve as a foundational guide for optimizing MM-ICL strategies in future research.

[Arxiv](https://arxiv.org/abs/2410.20482)