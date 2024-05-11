# 本文探讨了如何通过逻辑感知的课程调整方法，提升在知识图谱上进行复杂推理的性能。
发布时间：2024年05月02日

`知识图谱`
> Improving Complex Reasoning over Knowledge Graph with Logic-Aware Curriculum Tuning
>
> 处理不完全知识图谱上的复杂逻辑查询颇具挑战，过往研究多致力于通过神经网络学习实体/关系的嵌入及模拟一阶逻辑运算符。这些研究因无法有效共享世界知识以增强逻辑推理而受限，导致性能不尽人意。本论文提出了一种依托大型语言模型（LLMs）的复杂逻辑推理框架——LACT，内含基于课程的逻辑感知指令调整机制。我们采用二叉树分解技术增强一阶逻辑查询，以提升LLMs的推理能力。同时，为应对不同复杂查询间的难度差异，我们设计了一个简洁而高效的逻辑感知课程学习框架。实验结果表明，LACT在多个广泛使用的数据集上取得了显著的性能提升（平均MRR得分提高5.5%），刷新了最先进水平。相关代码和模型将不久后在GitHub和huggingface上线。
>
> https://arxiv.org/abs/2405.01649

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01649/x13.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.01649](https://arxiv.org/abs/2405.01649)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886