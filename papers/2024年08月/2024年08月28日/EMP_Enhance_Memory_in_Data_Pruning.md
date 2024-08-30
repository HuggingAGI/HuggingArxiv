# EMP：提升数据修剪中的记忆能力

发布时间：2024年08月28日

`LLM理论` `计算机视觉`

> EMP: Enhance Memory in Data Pruning

# 摘要

> 近期，大型语言与视觉模型表现卓越，但高昂的预训练与微调成本促使研究转向通过数据集精简加速训练。以往方法以样本损失为评判标准，力求挑选“难题”样本进行训练。然而，随着修剪率上升，各样本训练次数趋于均衡，导致众多关键或通用样本未能得到充分拟合，此现象我们称之为低频学习（LFL）。简言之，LFL限制了模型对多数样本的记忆。本研究中，我们剖析了LFL评分函数的构成，揭示其效率低下的理论根源，并提议在评分函数中引入记忆项，以强化模型记忆能力，同时对其进行近似处理。此外，我们首次探讨了自监督学习（SSL）中的记忆机制。借助对比学习，我们从理论与实践两方面推导出记忆项。最终，我们提出增强记忆修剪（EMP）策略，通过强化模型对数据的记忆，有效应对高修剪率下的记忆不足问题，进而提升模型性能。我们在图像分类、自然语言理解及模型预训练等多项任务中验证了EMP的效果。实证结果表明，即使在极端修剪率下，EMP亦能显著提升模型性能。以CIFAR100-ResNet50预训练任务为例，在70%修剪率下，EMP较现有方法性能提升达2.2%。

> Recently, large language and vision models have shown strong performance, but due to high pre-training and fine-tuning costs, research has shifted towards faster training via dataset pruning. Previous methods used sample loss as an evaluation criterion, aiming to select the most "difficult" samples for training. However, when the pruning rate increases, the number of times each sample is trained becomes more evenly distributed, which causes many critical or general samples to not be effectively fitted. We refer to this as Low-Frequency Learning (LFL). In other words, LFL prevents the model from remembering most samples. In our work, we decompose the scoring function of LFL, provide a theoretical explanation for the inefficiency of LFL, and propose adding a memory term to the scoring function to enhance the model's memory capability, along with an approximation of this memory term. Similarly, we explore memory in Self-Supervised Learning (SSL), marking the first discussion on SSL memory. Using contrastive learning, we derive the memory term both theoretically and experimentally. Finally, we propose Enhance Memory Pruning (EMP), which addresses the issue of insufficient memory under high pruning rates by enhancing the model's memory of data, thereby improving its performance. We evaluated the performance of EMP in tasks such as image classification, natural language understanding, and model pre-training. The results show that EMP can improve model performance under extreme pruning rates. For example, in the CIFAR100-ResNet50 pre-training task, with 70\% pruning, EMP outperforms current methods by 2.2\%.

[Arxiv](https://arxiv.org/abs/2408.16031)