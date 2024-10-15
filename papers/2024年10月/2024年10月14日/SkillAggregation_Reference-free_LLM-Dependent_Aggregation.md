# SkillAggregation: 一种无需参考、依赖于大型语言模型的聚合技术

发布时间：2024年10月14日

`LLM应用` `人工智能`

> SkillAggregation: Reference-free LLM-Dependent Aggregation

# 摘要

> 大型语言模型 (LLM) 因其生成类人判断的能力，正越来越多地用于评估 NLP 任务。虽然最初使用单个 LLM，但最新研究表明，多个 LLM 共同评判能显著提升性能。在利用多个判断时，关键步骤是聚合。现有 NLP 方法要么对所有 LLM 判断一视同仁，要么专为特定任务设计，如幻觉检测。本研究聚焦于无参考标签下的多系统预测聚合。我们提出了一种名为 SkillAggregation 的新方法，该方法无需额外数据或真实标签，即可智能组合 LLM 评判者的估计。它借鉴了图像分类领域的 Crowdlayer 聚合方法，并加以改进，以在推理过程中更有效地利用评判者的估计。在 HaluEval-Dialogue、TruthfulQA 和 Chatbot Arena 任务中，SkillAggregation 不仅在所有任务中超越了 Crowdlayer，更在多数任务中表现最佳，成为聚合方法中的佼佼者。

> Large Language Models (LLMs) are increasingly used to assess NLP tasks due to their ability to generate human-like judgments. Single LLMs were used initially, however, recent work suggests using multiple LLMs as judges yields improved performance. An important step in exploiting multiple judgements is the combination stage, aggregation. Existing methods in NLP either assign equal weight to all LLM judgments or are designed for specific tasks such as hallucination detection. This work focuses on aggregating predictions from multiple systems where no reference labels are available. A new method called SkillAggregation is proposed, which learns to combine estimates from LLM judges without needing additional data or ground truth. It extends the Crowdlayer aggregation method, developed for image classification, to exploit the judge estimates during inference. The approach is compared to a range of standard aggregation methods on HaluEval-Dialogue, TruthfulQA and Chatbot Arena tasks. SkillAggregation outperforms Crowdlayer on all tasks, and yields the best performance over all approaches on the majority of tasks.

[Arxiv](https://arxiv.org/abs/2410.10215)