# 基于 Transformer 的语言模型在描述逻辑 ALCQ 中的推理应用

发布时间：2024年10月12日

`LLM应用` `人工智能`

> Transformer-based Language Models for Reasoning in the Description Logic ALCQ

# 摘要

> 近期，基于transformer的语言模型在逻辑推理方面的研究备受关注。现有评估基准多为基础，仅涉及少量逻辑运算符和量词的一阶逻辑片段。我们采用表达性描述逻辑语言$\mathcal{ALCQ}$，构建了包含384K示例的自然语言数据集DELTA$_D$，并从推理深度和语言复杂性两方面进行扩展。通过此方法，我们深入探讨了经监督微调的DeBERTa模型及GPT-3.5、GPT-4在少样本提示下的逻辑推理能力。实验表明，经DELTA$_D$微调的DeBERTa模型在蕴涵检查任务中表现出色，而GPT系列模型在仅提供少量样本（9个）时，性能亦显著提升。我们已将相关代码和数据集开源。

> Recent advancements in transformer-based language models have sparked research into their logical reasoning capabilities. Most of the benchmarks used to evaluate these models are simple: generated from short (fragments of) first-order logic sentences with only a few logical operators and quantifiers. We construct the natural language dataset, DELTA$_D$, using the expressive description logic language $\mathcal{ALCQ}$. DELTA$_D$ comprises 384K examples and increases in two dimensions: i) reasoning depth, and ii) linguistic complexity. In this way, we systematically investigate the logical reasoning capabilities of a supervised fine-tuned DeBERTa-based model and two large language models (GPT-3.5, GPT-4) with few-shot prompting. We show that the DeBERTa-based model fine-tuned on our dataset can master the entailment checking task. Moreover, the performance of GPTs can improve significantly even when a small number of samples is provided (9 shots). We open-source our code and datasets.

[Arxiv](https://arxiv.org/abs/2410.09613)