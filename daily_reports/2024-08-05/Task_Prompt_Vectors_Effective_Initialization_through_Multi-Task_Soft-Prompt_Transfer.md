# 任务提示向量：借助多任务软提示转移，实现高效初始化
发布时间：2024年08月02日

`提示工程`
> Task Prompt Vectors: Effective Initialization through Multi-Task Soft-Prompt Transfer
>
> Prompt tuning 为 LLM 提供了一种模块化且高效训练方法，特别适合多任务场景。然而，现有的软提示方法在追求多任务适应性时，往往需要重复训练，降低了效率。我们提出的任务提示向量，通过计算软提示权重与初始化之间的差异，有效解决了这一问题。实验表明，这些向量能在资源有限的情况下，为相似任务提供有效的提示调整初始化。更重要的是，任务提示向量不受随机初始化的影响，支持跨任务的提示算术操作，从而在某些场景下超越了现有技术水平。
>
> https://arxiv.org/abs/2408.01119

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/arithmetics_first_page.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01119/x10.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.01119](https://arxiv.org/abs/2408.01119)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)