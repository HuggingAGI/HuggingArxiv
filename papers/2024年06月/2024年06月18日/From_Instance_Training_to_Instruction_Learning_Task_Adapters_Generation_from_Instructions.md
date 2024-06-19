# 从实例训练转向指令学习：基于指令的任务适配器生成

发布时间：2024年06月18日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在处理不同任务时的泛化能力，特别是在标记实例稀缺的情况下。通过提出基于指令的任务适配器生成（TAGI），该论文展示了如何通过模拟人类学习方式来提升LLMs的跨任务泛化能力，而无需依赖大量任务数据进行实例训练。这种方法通过知识蒸馏和两阶段训练（超网络预训练和微调）来实现，旨在降低计算成本并提高模型性能。因此，这篇论文属于LLM应用类别，因为它专注于改进LLMs在实际应用中的性能和效率。` `人工智能` `机器学习`

> From Instance Training to Instruction Learning: Task Adapters Generation from Instructions

# 摘要

> 大型语言模型（LLMs）通过指令微调（IFT）掌握了处理各类任务的技巧，但IFT仍依赖大量任务数据进行实例训练，这在标记实例稀缺的现实世界中限制了LLMs的灵活性，此时任务泛化能力显得尤为重要。相比之下，人类不仅通过反复练习，还通过理解指导原则来掌握技能和完成任务。本文模拟人类学习方式，旨在克服实例训练的局限，通过指令学习提升跨任务泛化能力。我们提出了基于指令的任务适配器生成（TAGI），它根据任务指令自动生成特定任务模型，无需重新训练以适应新任务。通过知识蒸馏，TAGI与通过实例训练开发的模型在标签、输出对数和适配器参数上保持一致。TAGI通过包含超网络预训练和微调的两阶段训练，获得了跨任务泛化能力。在Super-Natural Instructions和P3数据集上的测试显示，TAGI不仅与传统元训练模型和其他超网络模型媲美，甚至更胜一筹，同时大幅降低了计算成本。

> Large language models (LLMs) have acquired the ability to solve general tasks by utilizing instruction finetuning (IFT). However, IFT still relies heavily on instance training of extensive task data, which greatly limits the adaptability of LLMs to real-world scenarios where labeled task instances are scarce and broader task generalization becomes paramount. Contrary to LLMs, humans acquire skills and complete tasks not merely through repeated practice but also by understanding and following instructional guidelines. This paper is dedicated to simulating human learning to address the shortcomings of instance training, focusing on instruction learning to enhance cross-task generalization. Within this context, we introduce Task Adapters Generation from Instructions (TAGI), which automatically constructs the task-specific model in a parameter generation manner based on the given task instructions without retraining for unseen tasks. Specifically, we utilize knowledge distillation to enhance the consistency between TAGI developed through Learning with Instruction and task-specific models developed through Training with Instance, by aligning the labels, output logits, and adapter parameters between them. TAGI is endowed with cross-task generalization capabilities through a two-stage training process that includes hypernetwork pretraining and finetuning. We evaluate TAGI on the Super-Natural Instructions and P3 datasets. The experimental results demonstrate that TAGI can match or even outperform traditional meta-trained models and other hypernetwork models, while significantly reducing computational requirements.

![从实例训练转向指令学习：基于指令的任务适配器生成](../../../paper_images/2406.12382/x1.png)

![从实例训练转向指令学习：基于指令的任务适配器生成](../../../paper_images/2406.12382/x2.png)

![从实例训练转向指令学习：基于指令的任务适配器生成](../../../paper_images/2406.12382/x3.png)

![从实例训练转向指令学习：基于指令的任务适配器生成](../../../paper_images/2406.12382/x4.png)

[Arxiv](https://arxiv.org/abs/2406.12382)