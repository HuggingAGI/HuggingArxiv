# MMPT：零-shot 指令学习的多模态提示调优

发布时间：2024年09月23日

`LLM应用` `人工智能` `计算机视觉`

> MMPT: Multimodal Prompt Tuning for Zero-shot Instruction Learning

# 摘要

> 多模态大型语言模型 (MLLM) 在多个领域表现出色，尤其在提升对未见任务的零-shot 泛化能力方面备受关注。指令调优通过微调多模态任务中的预训练模型，成为实现零-shot 泛化的有效手段。随着 MLLM 规模的扩大，参数高效微调变得尤为重要。然而，现有方法多聚焦于单一模态，忽视了多模态特性。为此，我们提出了多模态提示调优 (MMPT) 方法，通过在微调中整合视觉与文本提示，促进跨模态特征的提取与对齐。实证结果显示，MMPT 在多模态数据集上表现优异，超越了多个最先进基线。全面的消融研究进一步证实了其设计与效率。

> Multimodal Large Language Models (MLLMs) demonstrate remarkable performance across a wide range of domains, with increasing emphasis on enhancing their zero-shot generalization capabilities for unseen tasks across various modalities. Instruction tuning has emerged as an effective strategy for achieving zero-shot generalization by finetuning pretrained models on diverse multimodal tasks. As the scale of MLLMs continues to grow, parameter-efficient finetuning becomes increasingly critical. However, most existing parameter-efficient approaches focus only on single modalities and often overlook the multimodal characteristics during finetuning. In this work, we introduce a novel Multimodal Prompt Tuning (MMPT) approach for efficient instruction tuning of MLLMs. MMPT effectively integrates visual and textual prompts into the vision encoder and language processor respectively during finetuning, facilitating the extraction and alignment of features across modalities. Empirical results on various multimodal evaluation datasets demonstrate the superior performance of our approach compared to several state-of-the-art baselines. A comprehensive set of ablation studies validates the effectiveness of our prompt design and the efficiency of our approach.

[Arxiv](https://arxiv.org/abs/2409.15657)