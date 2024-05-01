# StablePT：探索通过输入分离技术，为少样本学习提供稳定提示的新路径。

发布时间：2024年04月30日

`LLM应用` `人工智能` `机器学习`

> StablePT: Towards Stable Prompting for Few-shot Learning via Input Separation

# 摘要

> 大型语言模型通过提示学习，已经证明了在数据匮乏环境下成为高效的少次学习者的能力，这一进步彻底革新了学习模式。然而，这种方法的成效极大依赖于提示的初始设置质量，且在不同执行过程中波动较大。这种不稳定性使得提示调整变得不够可靠，容易受到不良提示的影响，限制了其在现实世界应用中的推广。为了应对这一挑战，我们提出了一种新方法，将硬提示和软提示作为独立的输入项，以减少由提示初始化引入的噪声。同时，我们采用对比学习方法对软提示进行优化，以便在训练过程中利用类别相关的信息，从而保持模型性能。实验结果显示，\sysname 在准确度上超越了当前最先进方法7.20%，并将平均标准偏差降低了2.02。此外，通过在7个不同任务的数据集上进行的广泛实验，证明了其鲁棒性和稳定性。

> Large language models have shown their ability to become effective few-shot learners with prompting, revoluting the paradigm of learning with data scarcity. However, this approach largely depends on the quality of prompt initialization, and always exhibits large variability among different runs. Such property makes prompt tuning highly unreliable and vulnerable to poorly constructed prompts, which limits its extension to more real-world applications. To tackle this issue, we propose to treat the hard prompt and soft prompt as separate inputs to mitigate noise brought by the prompt initialization. Furthermore, we optimize soft prompts with contrastive learning for utilizing class-aware information in the training process to maintain model performance. Experimental results demonstrate that \sysname outperforms state-of-the-art methods by 7.20% in accuracy and reduces the standard deviation by 2.02 on average. Furthermore, extensive experiments underscore its robustness and stability across 7 datasets covering various tasks.

[Arxiv](https://arxiv.org/abs/2404.19335)