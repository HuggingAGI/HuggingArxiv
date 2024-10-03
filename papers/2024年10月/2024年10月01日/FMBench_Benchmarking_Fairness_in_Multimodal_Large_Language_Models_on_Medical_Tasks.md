# FMBench：医疗任务中多模态大型语言模型公平性的基准测试

发布时间：2024年10月01日

`LLM应用` `人工智能`

> FMBench: Benchmarking Fairness in Multimodal Large Language Models on Medical Tasks

# 摘要

> 多模态大型语言模型 (MLLM) 在医疗任务如视觉问答 (VQA) 和报告生成 (RG) 中的表现显著提升。然而，这些模型在不同人群中的公平性仍未得到充分研究，尽管这在医疗领域至关重要。现有医疗多模态数据集的人口多样性不足，使得公平性评估变得复杂。为此，我们推出了 FMBench，首个评估 MLLM 在多样人口属性上公平性的基准。FMBench 包含四个人口属性（种族、民族、语言、性别），在零-shot 设置下应用于 VQA 和 RG 任务。我们的 VQA 任务采用自由形式，增强现实应用并减少预定义偏见。评估指标包括词汇和基于 LLM 的临床相关指标，以及新引入的公平性意识性能 (FAP) 指标。我们评估了八个最先进的开源 MLLM，涵盖 7B 到 26B 参数。FMBench 旨在帮助研究社区改进模型评估，推动领域进步。所有数据和代码将在接受后公开。

> Advancements in Multimodal Large Language Models (MLLMs) have significantly improved medical task performance, such as Visual Question Answering (VQA) and Report Generation (RG). However, the fairness of these models across diverse demographic groups remains underexplored, despite its importance in healthcare. This oversight is partly due to the lack of demographic diversity in existing medical multimodal datasets, which complicates the evaluation of fairness. In response, we propose FMBench, the first benchmark designed to evaluate the fairness of MLLMs performance across diverse demographic attributes. FMBench has the following key features: 1: It includes four demographic attributes: race, ethnicity, language, and gender, across two tasks, VQA and RG, under zero-shot settings. 2: Our VQA task is free-form, enhancing real-world applicability and mitigating the biases associated with predefined choices. 3: We utilize both lexical metrics and LLM-based metrics, aligned with clinical evaluations, to assess models not only for linguistic accuracy but also from a clinical perspective. Furthermore, we introduce a new metric, Fairness-Aware Performance (FAP), to evaluate how fairly MLLMs perform across various demographic attributes. We thoroughly evaluate the performance and fairness of eight state-of-the-art open-source MLLMs, including both general and medical MLLMs, ranging from 7B to 26B parameters on the proposed benchmark. We aim for FMBench to assist the research community in refining model evaluation and driving future advancements in the field. All data and code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2410.01089)