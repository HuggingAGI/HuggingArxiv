# SEA-SQL：融合语义增强与自适应细化的文本转SQL技术
发布时间：2024年08月09日

`代码编写`
> SEA-SQL: Semantic-Enhanced Text-to-SQL with Adaptive Refinement
>
> 大型语言模型 (LLM) 的最新进展极大地推动了 Text-to-SQL 任务的发展。在这些研究中，多数需要对生成的 SQL 查询进行后校正，主要通过分析错误案例来设计规则，以消除模型偏差，但缺乏对 SQL 查询的执行验证。此外，当前主流技术多依赖于 GPT-4 和少样本提示，成本高昂。为此，我们提出了语义增强的自适应细化 Text-to-SQL (SEA-SQL)，通过自适应偏差消除和动态执行调整，旨在提升性能的同时降低资源消耗，采用零样本提示。SEA-SQL 利用语义增强模式来丰富数据库信息并优化 SQL 查询，通过微调的自适应偏差消除器来减少 LLM 固有偏差，并进行动态执行调整以确保查询的可执行性。实验结果显示，SEA-SQL 在 GPT3.5 环境下以 9%-58% 的成本达到了行业领先水平，且与 GPT-4 性能相当，成本仅为其 0.9%-5.3%。
>
> https://arxiv.org/abs/2408.04919

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.04919](https://arxiv.org/abs/2408.04919)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)