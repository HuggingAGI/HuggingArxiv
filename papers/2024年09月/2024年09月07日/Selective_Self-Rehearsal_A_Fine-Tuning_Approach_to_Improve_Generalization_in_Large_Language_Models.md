# 选择性自我演练：一种微调策略，旨在提升大型语言模型的泛化性能

发布时间：2024年09月07日

`LLM理论` `人工智能` `机器学习`

> Selective Self-Rehearsal: A Fine-Tuning Approach to Improve Generalization in Large Language Models

# 摘要

> 微调 LLM 以提升特定任务性能虽常见，但常导致过拟合，使模型失去泛化能力。本文提出选择性自我演练 (SSR)，在保持与标准监督微调 (SFT) 相当性能的同时，提升泛化能力。SSR 利用查询的多重有效响应，通过正确响应减少微调中的模型专业化。实验表明，标准 SFT 在多个基准测试中性能下降高达 16.7%，而 SSR 仅下降约 2%，显示出更强的泛化能力。

> Fine-tuning Large Language Models (LLMs) on specific datasets is a common practice to improve performance on target tasks. However, this performance gain often leads to overfitting, where the model becomes too specialized in either the task or the characteristics of the training data, resulting in a loss of generalization. This paper introduces Selective Self-Rehearsal (SSR), a fine-tuning approach that achieves performance comparable to the standard supervised fine-tuning (SFT) while improving generalization. SSR leverages the fact that there can be multiple valid responses to a query. By utilizing the model's correct responses, SSR reduces model specialization during the fine-tuning stage. SSR first identifies the correct model responses from the training set by deploying an appropriate LLM as a judge. Then, it fine-tunes the model using the correct model responses and the gold response for the remaining samples. The effectiveness of SSR is demonstrated through experiments on the task of identifying unanswerable queries across various datasets. The results show that standard SFT can lead to an average performance drop of up to $16.7\%$ on multiple benchmarks, such as MMLU and TruthfulQA. In contrast, SSR results in close to $2\%$ drop on average, indicating better generalization capabilities compared to standard SFT.

[Arxiv](https://arxiv.org/abs/2409.04787)