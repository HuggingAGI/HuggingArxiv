# SLMRec：小型语言模型在序列推荐中的赋能
发布时间：2024年05月28日

`推荐系统`
> SLMRec: Empowering Small Language Models for Sequential Recommendation
>
> 序列推荐（SR）任务旨在预测用户基于其历史交互可能选择的下一个物品。SR模型通过分析用户行为序列来揭示复杂的行为模式和时间动态。近期研究表明，大型语言模型（LLMs）对SR系统影响深远，无论是将其视为语言建模还是用户表示的核心。尽管这些方法性能卓越，但对于在SR场景中是否必需大型语言模型及其规模大小，证据尚不充分。此外，由于LLMs的庞大体积，在需每日处理海量数据的真实应用中使用它们既不经济也不实际。本文通过大规模工业数据集的实验，揭示了LLMs深度的重要性，并意外发现多数中间层实为冗余。基于这一发现，我们开发了SLMRec，一种专为SR优化的小型语言模型，采用高效的知识蒸馏技术。SLMRec与其他提升效率的后处理技术兼容，如量化和剪枝。实验结果显示，SLMRec以仅13%的LLM模型参数，实现了训练和推理速度的显著提升（分别达6.6倍和8.0倍），同时保持了顶尖性能。
>
> https://arxiv.org/abs/2405.17890

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/traininfer.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17890/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.17890](https://arxiv.org/abs/2405.17890)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886