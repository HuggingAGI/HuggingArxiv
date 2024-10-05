# CHASE-SQL：优化文本到SQL转换中的多路径推理与候选选择
发布时间：2024年10月02日

`代码编写`
> CHASE-SQL: Multi-Path Reasoning and Preference Optimized Candidate Selection in Text-to-SQL
>
> 在解决 Text-to-SQL 任务中 LLM 的性能难题时，我们推出了 CHASE-SQL 框架。该框架通过多代理建模中的测试时间计算，创新性地提升了候选 SQL 查询的生成与选择。CHASE-SQL 利用 LLM 的内在知识，采用三种策略生成高质量 SQL 候选：分解复杂查询、基于执行计划的链式推理，以及定制化的少样本示例生成。通过微调的二进制候选选择 LLM 进行成对比较，选择代理能更稳健地选出最佳候选。CHASE-SQL 不仅提升了 SQL 查询的质量与多样性，还在 BIRD Text-to-SQL 数据集上以 73.0% 和 73.01% 的执行准确率刷新了记录，成为当时的排行榜冠军。
>
> https://arxiv.org/abs/2410.01943

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.01943](https://arxiv.org/abs/2410.01943)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)