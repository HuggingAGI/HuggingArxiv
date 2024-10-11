# 采样识别：多模态大型语言模型风险控制与评估的通用方案

发布时间：2024年10月10日

`LLM应用` `人工智能` `视频问答`

> Sample then Identify: A General Framework for Risk Control and Assessment in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLM) 在多个任务中展现了显著进步，但仍存在可信度问题。以往研究通过分割置信预测 (SCP) 构建预测集，但常依赖内部模型逻辑或限于多项选择，限制了其在动态开放环境中的应用。本文提出 TRON，一个适用于任何 MLLM 的风险控制与评估框架，支持开放与封闭场景的采样。TRON 包含两个核心组件：一是创新置信分数，采样最小响应集；二是非一致性分数，基于自一致性理论筛选高质量响应，通过两级风险控制错误率。此外，首次探讨开放环境中预测集的语义冗余，提出基于平均集大小的 MLLM 评估指标。实验表明，TRON 在四个视频问答数据集上，使用八个 MLLM，实现了用户指定风险水平内的期望错误率。去重预测集在保持适应性的同时，风险评估更高效稳定。

> Multimodal Large Language Models (MLLMs) exhibit promising advancements across various tasks, yet they still encounter significant trustworthiness issues. Prior studies apply Split Conformal Prediction (SCP) in language modeling to construct prediction sets with statistical guarantees. However, these methods typically rely on internal model logits or are restricted to multiple-choice settings, which hampers their generalizability and adaptability in dynamic, open-ended environments. In this paper, we introduce TRON, a two-step framework for risk control and assessment, applicable to any MLLM that supports sampling in both open-ended and closed-ended scenarios. TRON comprises two main components: (1) a novel conformal score to sample response sets of minimum size, and (2) a nonconformity score to identify high-quality responses based on self-consistency theory, controlling the error rates by two specific risk levels. Furthermore, we investigate semantic redundancy in prediction sets within open-ended contexts for the first time, leading to a promising evaluation metric for MLLMs based on average set size. Our comprehensive experiments across four Video Question-Answering (VideoQA) datasets utilizing eight MLLMs show that TRON achieves desired error rates bounded by two user-specified risk levels. Additionally, deduplicated prediction sets maintain adaptiveness while being more efficient and stable for risk assessment under different risk levels.

[Arxiv](https://arxiv.org/abs/2410.08174)