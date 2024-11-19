# 在多模态大型语言模型的微调过程中，既要从下游学习，也要保持自我特性。

发布时间：2024年11月16日

`LLM应用` `计算机视觉`

> Learn from Downstream and Be Yourself in Multimodal Large Language Model Fine-Tuning

# 摘要

> 多模态大型语言模型（MLLM）在不同分布和任务中都显示出强大的泛化能力，这主要得益于丰富的预训练数据集。微调 MLLM 已成为提升特定下游任务性能的常用手段。但在微调时，MLLM 常面临遗忘预训练所得知识的风险，从而致使泛化能力降低。为平衡泛化与专业化的关系，我们依据冻结的预训练权重幅度和累积的微调梯度值，提议衡量预训练和微调分布的参数重要性。我们还应用了重要性感知的权重分配策略，有针对性地更新下游任务中相对重要的参数。我们通过多种 MLLM 架构，在图像描述和视觉问答任务上进行了实证评估。全面的实验分析表明了所提方案的有效性，凸显了关键模块在增强 MLLM 微调的下游专业化性能、同时缓解泛化能力退化方面的高效性。

> Multimodal Large Language Model (MLLM) have demonstrated strong generalization capabilities across diverse distributions and tasks, largely due to extensive pre-training datasets. Fine-tuning MLLM has become a common practice to improve performance on specific downstream tasks. However, during fine-tuning, MLLM often faces the risk of forgetting knowledge acquired during pre-training, which can result in a decline in generalization abilities. To balance the trade-off between generalization and specialization, we propose measuring the parameter importance for both pre-trained and fine-tuning distributions, based on frozen pre-trained weight magnitude and accumulated fine-tuning gradient values. We further apply an importance-aware weight allocation strategy, selectively updating relatively important parameters for downstream tasks. We conduct empirical evaluations on both image captioning and visual question-answering tasks using various MLLM architectures. The comprehensive experimental analysis demonstrates the effectiveness of the proposed solution, highlighting the efficiency of the crucial modules in enhancing downstream specialization performance while mitigating generalization degradation in MLLM Fine-Tuning.

[Arxiv](https://arxiv.org/abs/2411.10928)