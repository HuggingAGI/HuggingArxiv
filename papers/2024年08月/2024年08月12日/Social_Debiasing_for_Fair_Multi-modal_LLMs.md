# 多模态大型语言模型的社会去偏见研究

发布时间：2024年08月12日

`LLM应用` `人工智能` `社会科学`

> Social Debiasing for Fair Multi-modal LLMs

# 摘要

> 多模态大型语言模型 (MLLMs) 虽已大幅进步，具备强大的视觉-语言理解力，但常因训练数据中的社会偏见而产生不公预测。为此，我们 i) 推出包含多元社会概念的反事实数据集 (CMSC)，以更丰富、更广泛的数据集超越现有水平。ii) 创新提出反刻板印象去偏策略 (ASD)，通过优化训练流程、调整损失函数及改进数据采样，有效对抗偏见。实验证明，CMSC 与 ASD 联手，在保持性能的同时，显著降低社会偏见。

> Multi-modal Large Language Models (MLLMs) have advanced significantly, offering powerful vision-language understanding capabilities. However, these models often inherit severe social biases from their training datasets, leading to unfair predictions based on attributes like race and gender. This paper addresses the issue of social biases in MLLMs by i) Introducing a comprehensive Counterfactual dataset with Multiple Social Concepts (CMSC), which provides a more diverse and extensive training set compared to existing datasets. ii) Proposing an Anti-Stereotype Debiasing strategy (ASD). Our method works by revisiting the MLLM training process, rescaling the autoregressive loss function, and improving data sampling methods to counteract biases. Through extensive experiments on various MLLMs, our CMSC dataset and ASD method demonstrate a significant reduction in social biases while maintaining the models' original performance.

[Arxiv](https://arxiv.org/abs/2408.06569)