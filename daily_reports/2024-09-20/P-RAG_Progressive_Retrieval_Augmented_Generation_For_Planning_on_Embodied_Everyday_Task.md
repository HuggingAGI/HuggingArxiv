# P-RAG：渐进式检索增强生成，专为实体日常任务规划而生
发布时间：2024年09月17日

`RAG`
> P-RAG: Progressive Retrieval Augmented Generation For Planning on Embodied Everyday Task
>
> Embodied Everyday Task 在 embodied AI 领域颇受欢迎，要求代理根据自然语言指令和视觉观察执行一系列动作。传统方法面临两大挑战：自然语言指令缺乏明确任务规划，且需大量训练才能掌握任务环境知识。基于大型语言模型 (LLM) 的先前工作要么因缺乏特定任务知识而表现不佳，要么依赖少量真实样本。为解决这些问题，我们提出了 Progressive Retrieval Augmented Generation (P-RAG) 方法，既充分利用 LLM 的语言处理能力，又逐步积累特定任务知识，无需真实数据。与传统一次性检索辅助生成的方法不同，P-RAG 采用迭代方式逐步更新数据库，每次迭代都从前次交互中获取历史信息作为经验参考。我们还引入了更细粒度的检索方案，不仅检索类似任务，还结合类似情况，提供更有价值的参考经验。实验证明，P-RAG 在不使用真实数据的情况下表现优异，甚至可通过自我迭代进一步提升性能。
>
> https://arxiv.org/abs/2409.11279

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.11279](https://arxiv.org/abs/2409.11279)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)