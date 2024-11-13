# PDC 和 DM-SFT：一条用于增强大型语言模型 SQL 错误修复的道路
发布时间：2024年11月11日

`代码编写`
> PDC & DM-SFT: A Road for LLM SQL Bug-Fix Enhancing
>
> 代码大型语言模型（Code LLMs），如 Code llama 和 DeepSeek-Coder，在代码生成任务中表现出色。然而，大多数现有的模型专注于生成正确代码的能力，但在错误修复方面常常遇到困难。我们引入了一套方法来增强 LLM 的 SQL 错误修复能力。这些方法主要由两部分组成：从头开始的渐进式数据集构建（PDC）和动态掩码监督微调（DM-SFT）。PDC 分别从广度优先和深度优先的角度提出了两种数据扩展方法。DM-SFT 引入了一种高效的错误修复监督学习方法，有效地减少了总训练步骤，并减轻了 SQL 代码错误修复训练中的“迷失方向”。在我们的评估中，用这两种方法训练的代码 LLM 模型超过了所有当前性能最佳但规模大得多的模型。
>
> https://arxiv.org/abs/2411.06767

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.06767](https://arxiv.org/abs/2411.06767)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)