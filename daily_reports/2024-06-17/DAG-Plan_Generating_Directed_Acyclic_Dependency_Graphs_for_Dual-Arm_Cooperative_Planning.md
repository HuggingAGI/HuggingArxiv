# DAG-Plan：构建双臂协同规划的有向无环依赖图
发布时间：2024年06月14日


> DAG-Plan: Generating Directed Acyclic Dependency Graphs for Dual-Arm Cooperative Planning
>
> 双臂机器人通过协同操作和任务执行，展现出比单臂机器人更高的灵活性和效率。然而，对于复杂的长远任务，如何有效协调双臂仍是一大挑战。现有的任务规划方法多针对单臂机器人，未能充分发挥双臂系统的潜力。为此，我们推出了DAG-Plan，一个专为双臂机器人设计的任务规划框架。该框架利用LLMs将复杂任务分解为可执行的子任务，并通过有向无环图（DAG）进行表示。关键在于，DAG-Plan能根据实时环境动态分配任务给合适的手臂，实现高效并行执行。在双臂厨房基准测试中，DAG-Plan的表现显著优于传统方法，效率提升近50%，成功率更是翻倍。
>
> https://arxiv.org/abs/2406.09953

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/baxter.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x21.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x22.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x23.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x24.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09953/x25.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09953](https://arxiv.org/abs/2406.09953)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2