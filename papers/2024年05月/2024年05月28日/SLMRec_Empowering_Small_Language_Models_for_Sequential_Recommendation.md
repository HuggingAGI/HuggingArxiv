# SLMRec：小型语言模型在序列推荐中的赋能

发布时间：2024年05月28日

`LLM应用

这篇论文主要探讨了在序列推荐（SR）任务中使用大型语言模型（LLMs）的必要性和效率问题。通过实验分析，论文发现大型语言模型中的许多中间层可能是冗余的，并据此开发了一种小型语言模型SLMRec，该模型通过知识蒸馏技术优化，以较少的参数实现了高效的训练和推理速度，同时保持了高性能。这一研究直接应用于实际的序列推荐系统中，优化了模型的大小和效率，属于LLM应用的范畴。` `推荐系统` `电子商务`

> SLMRec: Empowering Small Language Models for Sequential Recommendation

# 摘要

> 序列推荐（SR）任务旨在预测用户基于其历史交互可能选择的下一个物品。SR模型通过分析用户行为序列来揭示复杂的行为模式和时间动态。近期研究表明，大型语言模型（LLMs）对SR系统影响深远，无论是将其视为语言建模还是用户表示的核心。尽管这些方法性能卓越，但对于在SR场景中是否必需大型语言模型及其规模大小，证据尚不充分。此外，由于LLMs的庞大体积，在需每日处理海量数据的真实应用中使用它们既不经济也不实际。本文通过大规模工业数据集的实验，揭示了LLMs深度的重要性，并意外发现多数中间层实为冗余。基于这一发现，我们开发了SLMRec，一种专为SR优化的小型语言模型，采用高效的知识蒸馏技术。SLMRec与其他提升效率的后处理技术兼容，如量化和剪枝。实验结果显示，SLMRec以仅13%的LLM模型参数，实现了训练和推理速度的显著提升（分别达6.6倍和8.0倍），同时保持了顶尖性能。

> The sequential Recommendation (SR) task involves predicting the next item a user is likely to interact with, given their past interactions. The SR models examine the sequence of a user's actions to discern more complex behavioral patterns and temporal dynamics. Recent research demonstrates the great impact of LLMs on sequential recommendation systems, either viewing sequential recommendation as language modeling or serving as the backbone for user representation. Although these methods deliver outstanding performance, there is scant evidence of the necessity of a large language model and how large the language model is needed, especially in the sequential recommendation scene. Meanwhile, due to the huge size of LLMs, it is inefficient and impractical to apply a LLM-based model in real-world platforms that often need to process billions of traffic logs daily. In this paper, we explore the influence of LLMs' depth by conducting extensive experiments on large-scale industry datasets. Surprisingly, we discover that most intermediate layers of LLMs are redundant. Motivated by this insight, we empower small language models for SR, namely SLMRec, which adopt a simple yet effective knowledge distillation method. Moreover, SLMRec is orthogonal to other post-training efficiency techniques, such as quantization and pruning, so that they can be leveraged in combination. Comprehensive experimental results illustrate that the proposed SLMRec model attains the best performance using only 13% of the parameters found in LLM-based recommendation models, while simultaneously achieving up to 6.6x and 8.0x speedups in training and inference time costs, respectively.

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x1.png)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/traininfer.jpg)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x2.png)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x3.png)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x4.png)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x5.png)

![SLMRec：小型语言模型在序列推荐中的赋能](../../../paper_images/2405.17890/x6.png)

[Arxiv](https://arxiv.org/abs/2405.17890)