# [探究微调后大型语言模型的泛化威力](https://arxiv.org/abs/2403.09162)

发布时间：2024年03月14日

`LLM理论`

``

`模型泛化能力`

> Unveiling the Generalization Power of Fine-Tuned Large Language Models

> 虽然 LLM 在处理多种任务上表现卓越，但要使其在测试集上超越未经微调的同类模型，通常需要针对下游特定领域数据集进行微调。然而，微调对 LLM 泛化能力的整体影响尚不清晰。本研究对比分析了原始未改版 LLM 与其微调版本间的差异，核心问题在于微调是否会改变 LLM 本质的泛化能力。为了深入探究这个问题，我们在各类数据集上的五个不同语言任务中开展了大规模实验。实验结果显示，经过生成与分类任务微调的模型，在面对不同领域和任务时展现出各异的泛化特性。有趣的是，我们发现在生成任务微调阶段结合上下文学习策略能够提升模型的泛化性能。借此系统研究，我们期望能为 LLM 微调方法的发展提供宝贵的洞见。

> While Large Language Models (LLMs) have demonstrated exceptional multitasking abilities, fine-tuning these models on downstream, domain-specific datasets is often necessary to yield superior performance on test sets compared to their counterparts without fine-tuning. However, the comprehensive effects of fine-tuning on the LLMs' generalization ability are not fully understood. This paper delves into the differences between original, unmodified LLMs and their fine-tuned variants. Our primary investigation centers on whether fine-tuning affects the generalization ability intrinsic to LLMs. To elaborate on this, we conduct extensive experiments across five distinct language tasks on various datasets. Our main findings reveal that models fine-tuned on generation and classification tasks exhibit dissimilar behaviors in generalizing to different domains and tasks. Intriguingly, we observe that integrating the in-context learning strategy during fine-tuning on generation tasks can enhance the model's generalization ability. Through this systematic investigation, we aim to contribute valuable insights into the evolving landscape of fine-tuning practices for LLMs.

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x1.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x2.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x3.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x4.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x5.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x6.png)

![探究微调后大型语言模型的泛化威力](../../../paper_images/2403.09162/x7.png)