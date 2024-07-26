# System-1.x：探索语言模型中快速与慢速规划的平衡之道
发布时间：2024年07月19日


> System-1.x: Learning to Balance Fast and Slow Planning with Language Models
>
> 语言模型在解决长时程规划问题时，有两种模式：快速的“系统1”直接生成计划，无需搜索或回溯；慢速的“系统2”则通过逐步搜索可能动作来规划。尽管系统2更有效，但其高计算成本使其不适用于长计划或大动作空间。此外，单独的系统1或2无法满足用户对最终目标的控制需求。为此，我们设计了系统1.x规划器，这是一个结合了两种模式的混合规划框架，能根据问题难度灵活调整。系统1.x由控制器、系统1规划器和系统2规划器组成，通过用户设定的混合因子（x）来分配任务给系统1或2。我们在单一LLM基础上对这三个组件进行微调，仅依赖搜索轨迹进行监督。实验表明，系统1.x在迷宫导航和积木世界任务中表现优异，不仅超越了单一模式的规划器，还展示了其可控性、灵活性和泛化性。
>
> https://arxiv.org/abs/2407.14414

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14414/x12.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.14414](https://arxiv.org/abs/2407.14414)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1