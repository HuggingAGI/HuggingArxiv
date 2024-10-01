# 多模态大型语言模型中的视觉问题分解

发布时间：2024年09月28日

`LLM应用` `人工智能` `计算机视觉`

> Visual Question Decomposition on Multimodal Large Language Models

# 摘要

> 问题分解是引导 LLM 回答复杂问题的有效方法。然而，现有研究主要集中在单模态模型上，而多模态大型语言模型 (MLLM) 的问题分解能力尚未被深入研究。本文针对 MLLM 进行了视觉问题分解的探索。我们设计了一个包含数据集和评估标准的系统框架，发现现有 MLLM 在生成高质量子问题方面存在困难。为此，我们提出了 DecoVQA+ 数据集和一套高效的微调流程，旨在提升模型的选择性分解能力。实验结果表明，经过微调的 MLLM 在子问题质量和选择性分解策略上均有显著提升，同时在 VQA 基准测试中也取得了更高的准确率。

> Question decomposition has emerged as an effective strategy for prompting Large Language Models (LLMs) to answer complex questions. However, while existing methods primarily focus on unimodal language models, the question decomposition capability of Multimodal Large Language Models (MLLMs) has yet to be explored. To this end, this paper explores visual question decomposition on MLLMs. Specifically, we introduce a systematic evaluation framework including a dataset and several evaluation criteria to assess the quality of the decomposed sub-questions, revealing that existing MLLMs struggle to produce high-quality sub-questions. To address this limitation, we propose a specific finetuning dataset, DecoVQA+, for enhancing the model's question decomposition capability. Aiming at enabling models to perform appropriate selective decomposition, we propose an efficient finetuning pipeline. The finetuning pipeline consists of our proposed dataset and a training objective for selective decomposition. Finetuned MLLMs demonstrate significant improvements in the quality of sub-questions and the policy of selective question decomposition. Additionally, the models also achieve higher accuracy with selective decomposition on VQA benchmark datasets.

[Arxiv](https://arxiv.org/abs/2409.19339)