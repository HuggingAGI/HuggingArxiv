# MCS-SQL：借助多重提示与选择题机制，精妙演绎文本至SQL的生成艺术
发布时间：2024年05月13日

`应用案例`
> MCS-SQL: Leveraging Multiple Prompts and Multiple-Choice Selection For Text-to-SQL Generation
>
> 大型语言模型（LLMs）的进步是基于上下文学习（ICL）的方法在文本到SQL任务中超越微调方法的关键。尽管如此，面对复杂模式和查询（如BIRD）的挑战，它们的表现仍不及人类专家。本研究深入探讨了LLMs对提示的敏感性，并提出了一种创新策略，通过多提示探索答案的广阔空间，并巧妙地整合结果。我们通过多提示的架构链接，精细地调整数据库架构。接着，我们依据这些精炼架构和多样提示，创造出多样的候选SQL查询。最后，我们依据置信度评分筛选这些候选查询，并通过多选机制，向LLM展示最优解。在BIRD和Spider的测试中，我们的方法分别实现了65.5%和89.6%的准确率，显著超越了以往的ICL方法，并在BIRD上以准确性和效率刷新了SOTA记录。
>
> https://arxiv.org/abs/2405.07467

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.07467/image.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.07467/error.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.07467](https://arxiv.org/abs/2405.07467)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886