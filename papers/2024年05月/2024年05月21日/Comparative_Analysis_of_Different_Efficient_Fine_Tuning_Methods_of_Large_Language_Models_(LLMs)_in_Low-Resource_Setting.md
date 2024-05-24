# 低资源环境下，大型语言模型（LLMs）高效微调方法的比较研究

发布时间：2024年05月21日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）的不同微调策略，包括少样本全模型微调（如Vanilla FT和PBFT）、情境学习（ICL）、自适应微调和LoRA适配器等，并在不同数据集上进行了详细的对比分析。这些内容主要关注LLM的理论和方法学层面，涉及模型微调的技术细节和性能评估，因此更适合归类于LLM理论。虽然论文中也涉及了一些应用层面的讨论，如微调策略的选择应基于可用资源和任务适应性，但核心内容更偏向于理论和技术探讨。` `机器学习`

> Comparative Analysis of Different Efficient Fine Tuning Methods of Large Language Models (LLMs) in Low-Resource Setting

# 摘要

> 在大型语言模型领域，研究表明少样本全模型微调（如Vanilla FT和PBFT）与情境学习（ICL）在处理域外数据集时表现相似，但在任务适应性上有所差异，且都面临内存需求的挑战。本文深入探讨了LLM的不同微调策略，并在两个不同数据集上与全模型微调进行了详细对比。实验从最先进的方法开始，如在COLA和MNLI数据集上对预训练模型进行vanilla微调和PBFT。接着，我们评估了自适应微调和LoRA适配器在少样本环境下的效率。最后，我们将最近流行的情境蒸馏方法与vanilla FT和PBFT进行了比较。研究发现，这些替代策略在域外数据集上的泛化能力与vanilla FT和PBFT相当，但PBFT在域外数据上的表现略逊于Vanilla FT，凸显了有效提示的重要性。自适应微调和LoRA实验与标准微调相比表现相当或稍差，而情境蒸馏实验则优于标准微调。这表明，选择微调方法应基于可用资源和任务适应性。

> In the domain of large language models (LLMs), arXiv:2305.16938 showed that few-shot full-model fine-tuning -- namely Vanilla Fine Tuning (FT) and Pattern-Based Fine Tuning (PBFT) --, and In-Context Learning (ICL) generalize similarly on Out-Of-Domain (OOD) datasets, but vary in terms of task adaptation. However, they both pose challenges, especially in term of memory requirements. In this paper, we further try to push the understanding of different fine-tuning strategies for LLM and aim to bring a myriad of these on the same pedestal for an elaborate comparison with full-model fine-tuning on two diverse datasets. To that end, we conducted a series of experiments, beginning with state-of-the-art methods like vanilla fine-tuning and Pattern-Based Fine-Tuning (PBFT) on pre-trained models across two datasets, COLA and MNLI. We then investigate adaptive fine-tuning and the efficiency of LoRA adapters in a few-shot setting. Finally, we also compare an alternative approach that has gained recent popularity -- context distillation -- with the vanilla FT and PBFT with and without few-shot setup.
  Our findings suggest that these alternative strategies that we explored can exhibit out-of-domain generalization comparable to that of vanilla FT and PBFT. PBFT under-performs Vanilla FT on out-of-domain (OOD) data, emphasizing the need for effective prompts. Further, our adaptive-fine tuning and LoRA experiments perform comparable or slightly worse than the standard fine-tunings as anticipated, since standard fine-tunings involve tuning the entire model. Finally, our context distillation experiments out-perform the standard fine-tuning methods. These findings underscore that eventually the choice of an appropriate fine-tuning method depends on the available resources (memory, compute, data) and task adaptability.

[Arxiv](https://arxiv.org/abs/2405.13181)