# 基于视觉语言模型的多智能体协同规划

发布时间：2024年08月10日

`Agent` `人工智能` `计算机视觉`

> Multi-agent Planning using Visual Language Models

# 摘要

> 大型语言模型 (LLM) 和视觉语言模型 (VLM) 因其跨领域的性能提升和应用而备受瞩目。然而，在需要深入理解问题领域时，这些模型可能产生错误结果，尤其是在同时进行规划和感知时，因难以整合多模态信息而受困。为解决此问题，我们提出了一种无需特定数据结构的多智能体实体任务规划架构，仅使用环境图像并借助常识知识处理自由领域。此外，我们引入了全自动评估程序 PG2S，以更精准地评估计划质量。通过 ALFRED 数据集的验证，我们将 PG2S 与 KAS 指标对比，进一步评估了生成计划的质量。

> Large Language Models (LLMs) and Visual Language Models (VLMs) are attracting increasing interest due to their improving performance and applications across various domains and tasks. However, LLMs and VLMs can produce erroneous results, especially when a deep understanding of the problem domain is required. For instance, when planning and perception are needed simultaneously, these models often struggle because of difficulties in merging multi-modal information. To address this issue, fine-tuned models are typically employed and trained on specialized data structures representing the environment. This approach has limited effectiveness, as it can overly complicate the context for processing. In this paper, we propose a multi-agent architecture for embodied task planning that operates without the need for specific data structures as input. Instead, it uses a single image of the environment, handling free-form domains by leveraging commonsense knowledge. We also introduce a novel, fully automatic evaluation procedure, PG2S, designed to better assess the quality of a plan. We validated our approach using the widely recognized ALFRED dataset, comparing PG2S to the existing KAS metric to further evaluate the quality of the generated plans.

[Arxiv](https://arxiv.org/abs/2408.05478)