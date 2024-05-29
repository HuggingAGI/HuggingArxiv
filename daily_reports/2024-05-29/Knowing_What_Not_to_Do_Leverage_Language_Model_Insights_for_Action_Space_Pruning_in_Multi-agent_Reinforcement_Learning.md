# 明智之举：借助语言模型洞察，精简多代理强化学习中的动作选择空间
发布时间：2024年05月27日

`多Agent应用`
> Knowing What Not to Do: Leverage Language Model Insights for Action Space Pruning in Multi-agent Reinforcement Learning
>
> 多代理强化学习（MARL）用于培养能在复杂环境中灵活运用合作或竞争策略的自主代理。但随着代理数量的增加，动作空间呈组合式膨胀，引发算法不稳定、收敛难题及局部最优陷阱。虽然研究者们已开发出多种算法来压缩动作空间，但这些方法也带来了新问题，如需人工先验知识或问题结构的依赖，限制了其应用范围。本文推出的进化动作空间缩减与知识（eSpark）框架，由大型语言模型（LLMs）驱动，旨在提升MARL中的探索效率并精简不必要动作。通过简单的任务概述提示，eSpark能零-shot生成探索函数，剔除冗余或无关的状态-动作对，并通过策略反馈实现自我优化。在15个场景的库存管理和交通灯控制任务中，eSpark均超越了传统MARL算法，分别实现了34.4%和9.9%的性能提升。此外，面对超过500个代理的挑战，eSpark展现了29.7%的扩展性改进。代码地址：https://github.com/LiuZhihao2022/eSpark.git。
>
> https://arxiv.org/abs/2405.16854

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16854/eSpark_improvement.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.16854](https://arxiv.org/abs/2405.16854)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886