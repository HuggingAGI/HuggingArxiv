# LoFiT：针对LLM表示的局部精细调整

发布时间：2024年06月03日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的内部表示调整，以适应新任务的方法。通过提出一种名为LoFiT的新框架，该研究专注于识别和优化对特定任务至关重要的注意力头子集，这种方法涉及理论层面的模型内部机制调整，而非直接的应用或Agent行为。因此，它更符合LLM理论的分类。` `机器学习`

> LoFiT: Localized Fine-tuning on LLM Representations

# 摘要

> 最新研究揭示，大型语言模型（LLMs）无需额外学习即可适应新任务，关键在于通过调整模型内部表示来引导期望行为。例如，为特定注意力头的输出添加特定偏置向量，能显著提升模型输出真实性。本研究提出了一种名为LoFiT的新框架，它通过识别对特定任务至关重要的注意力头子集，并训练相应的偏移向量，以微调模型在这些关键点的表示。LoFiT仅针对极少数头部（约3%）进行优化，且所需训练数据有限，与传统表示干预方法相当。在真实性和推理任务中，LoFiT的干预策略显示出比传统方法更高的适应效率。此外，针对特定任务选择注意力头的重要性凸显，特定任务的优化选择能带来更佳性能。尽管LoFiT修改的参数远少于其他方法，如LoRA，但在我们测试的任务上，其性能与之相当。

> Recent work in interpretability shows that large language models (LLMs) can be adapted for new tasks in a learning-free way: it is possible to intervene on LLM representations to elicit desired behaviors for alignment. For instance, adding certain bias vectors to the outputs of certain attention heads is reported to boost the truthfulness of models. In this work, we show that localized fine-tuning serves as an effective alternative to such representation intervention methods. We introduce a framework called Localized Fine-Tuning on LLM Representations (LoFiT), which identifies a subset of attention heads that are most important for learning a specific task, then trains offset vectors to add to the model's hidden representations at those selected heads. LoFiT localizes to a sparse set of heads (3%) and learns the offset vectors from limited training data, comparable to the settings used for representation intervention. For truthfulness and reasoning tasks, we find that LoFiT's intervention vectors are more effective for LLM adaptation than vectors from representation intervention methods such as Inference-time Intervention. We also find that the localization step is important: selecting a task-specific set of attention heads can lead to higher performance than intervening on heads selected for a different task. Finally, for the tasks we study, LoFiT achieves comparable performance to other parameter-efficient fine-tuning methods such as LoRA, despite modifying 20x-200x fewer parameters than these methods.

[Arxiv](https://arxiv.org/abs/2406.01563)