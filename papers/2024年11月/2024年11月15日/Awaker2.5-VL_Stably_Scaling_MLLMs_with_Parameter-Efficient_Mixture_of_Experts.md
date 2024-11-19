# Awaker2.5-VL：借助参数高效的专家混合实现大型多语言模型的稳定扩展

发布时间：2024年11月15日

`LLM应用` `多模态` `语言模型`

> Awaker2.5-VL: Stably Scaling MLLMs with Parameter-Efficient Mixture of Experts

# 摘要

> 随着多模态大型语言模型（MLLMs）研究的日益火热，先进的 MLLM 模型通常得同时应对各类文本和视觉任务（如 VQA、检测、OCR 及 ChartQA），以应用于实际场景。然而，由于不同任务数据在表征和分布上差异显著，简单地把所有任务的数据混在一起，会引发众所周知的“多任务冲突”问题，致使各任务的性能下滑。为解决此问题，我们推出了 Awaker2.5-VL，这是一种适用于 MLLM 的专家混合（MoE）架构，它借助多个稀疏激活的专家获取多任务能力。为加快 Awaker2.5-VL 的训练和推理，我们模型中的每个专家都被设计成低秩适应（LoRA）结构。在多个最新基准上的大量实验验证了 Awaker2.5-VL 的有效性。代码和模型权重已在我们的项目页面发布：https://github.com/MetabrainAGI/Awaker。

> As the research of Multimodal Large Language Models (MLLMs) becomes popular, an advancing MLLM model is typically required to handle various textual and visual tasks (e.g., VQA, Detection, OCR, and ChartQA) simultaneously for real-world applications. However, due to the significant differences in representation and distribution among data from various tasks, simply mixing data of all tasks together leads to the well-known``multi-task conflict" issue, resulting in performance degradation across various tasks. To address this issue, we propose Awaker2.5-VL, a Mixture of Experts~(MoE) architecture suitable for MLLM, which acquires the multi-task capabilities through multiple sparsely activated experts. To speed up the training and inference of Awaker2.5-VL, each expert in our model is devised as a low-rank adaptation (LoRA) structure. Extensive experiments on multiple latest benchmarks demonstrate the effectiveness of Awaker2.5-VL. The code and model weight are released in our Project Page: https://github.com/MetabrainAGI/Awaker.

[Arxiv](https://arxiv.org/abs/2411.10669)