# 对话状态跟踪中零样本领域适应的模式增强

发布时间：2024年10月31日

`LLM应用` `对话系统` `语言模型`

> Schema Augmentation for Zero-Shot Domain Adaptation in Dialogue State Tracking

# 摘要

> 在任务导向对话（TOD）系统中，对话状态跟踪（DST）的零样本领域适应一直是个难题，模型得推广到训练时没见过的目标领域。当下零样本领域适应的大型语言模型方法依靠提示来引入目标领域的相关知识。不过，其效果严重依赖提示工程和基础语言模型的零样本能力。在本研究中，我们设计了一种新的数据增强方法——模式增强，通过微调提升语言模型的零样本领域适应能力。模式增强是个简单却有效的技术，在提示所提供的模式里引入插槽名称的变化，从而增强泛化能力。在 MultiWOZ 和 SpokenWOZ 上的实验显示，所提方法比基线有大幅改进，在某些实验中，在未见过的领域实现了两倍多的准确率提升，同时在所有领域保持了同等或更优的性能。

> Zero-shot domain adaptation for dialogue state tracking (DST) remains a challenging problem in task-oriented dialogue (TOD) systems, where models must generalize to target domains unseen at training time. Current large language model approaches for zero-shot domain adaptation rely on prompting to introduce knowledge pertaining to the target domains. However, their efficacy strongly depends on prompt engineering, as well as the zero-shot ability of the underlying language model. In this work, we devise a novel data augmentation approach, Schema Augmentation, that improves the zero-shot domain adaptation of language models through fine-tuning. Schema Augmentation is a simple but effective technique that enhances generalization by introducing variations of slot names within the schema provided in the prompt. Experiments on MultiWOZ and SpokenWOZ showed that the proposed approach resulted in a substantial improvement over the baseline, in some experiments achieving over a twofold accuracy gain over unseen domains while maintaining equal or superior performance over all domains.

[Arxiv](https://arxiv.org/abs/2411.00150)