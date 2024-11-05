# 图上规划：大型语言模型在知识图谱上的自校正自适应规划
发布时间：2024年10月31日

`知识图谱`
> Plan-on-Graph: Self-Correcting Adaptive Planning of Large Language Model on Knowledge Graphs
>
> 大型语言模型（LLMs）在复杂任务上已经展现出了卓越的推理能力，但它们仍然存在知识过时、幻觉和决策不透明的问题。相比之下，知识图谱（KGs）可以为大型语言模型提供明确且可编辑的知识，以缓解这些问题。现有的知识图谱增强型大型语言模型范式手动预先定义探索空间的广度，并要求在知识图谱中完美导航。然而，这种范式不能根据问题语义自适应地探索知识图谱中的推理路径，也不能自我纠正错误的推理路径，从而导致效率和效果上的瓶颈。为了解决这些限制，我们提出了一种用于知识图谱增强型大型语言模型的新型自我纠正自适应规划范式，名为图上规划（PoG），它首先将问题分解为几个子目标，然后重复自适应探索推理路径、更新内存和反思是否需要自我纠正错误推理路径的过程，直到得出答案。具体来说，设计了指导、内存和反思这三个重要机制协同工作，以保证图推理的自我纠正规划的自适应广度。最后，在三个真实世界数据集上进行的大量实验证明了 PoG 的有效性和效率。
>
> https://arxiv.org/abs/2410.23875

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.23875](https://arxiv.org/abs/2410.23875)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)