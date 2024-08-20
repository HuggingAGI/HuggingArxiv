# 理性语言模型时代，文本到SQL转换是否宣告了模式链接的终结？
发布时间：2024年08月18日

`代码编写`
> The Death of Schema Linking? Text-to-SQL in the Age of Well-Reasoned Language Models
>
> Schema linking 在 Text-to-SQL 转换中至关重要，旨在筛选出相关表和列，同时忽略无关信息。然而，不完善的 schema linking 可能导致关键列被遗漏，影响查询准确性。我们研究发现，新一代 LLM 在生成过程中能自动识别相关 schema 元素，无需显式 schema linking。因此，Text-to-SQL 管道可直接传递完整数据库 schema 给 LLM，避免信息遗漏。我们还提出了替代 schema linking 的技术，确保在不牺牲关键 schema 信息的前提下提升转换准确性。我们的方法在 BIRD 基准测试中以 71.83% 的执行准确率领先。
>
> https://arxiv.org/abs/2408.07702

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.07702/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.07702/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.07702/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.07702/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.07702/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.07702](https://arxiv.org/abs/2408.07702)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)