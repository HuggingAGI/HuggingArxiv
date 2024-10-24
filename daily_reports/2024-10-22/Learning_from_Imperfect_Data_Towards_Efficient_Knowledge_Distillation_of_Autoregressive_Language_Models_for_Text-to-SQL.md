# 从不完美数据中学习：提升自动回归语言模型在文本到SQL任务中的知识蒸馏效率
发布时间：2024年10月15日

`代码编写`
> Learning from Imperfect Data: Towards Efficient Knowledge Distillation of Autoregressive Language Models for Text-to-SQL
>
> 大型语言模型（LLM）在将自然语言问题转换为 SQL 查询方面表现出色，但这些模型计算成本高，难以在实际应用中部署，因此压缩它们显得尤为重要。知识蒸馏（KD）是一种常见方法，旨在将大模型精简为小模型。尽管针对自回归 LLM 的 KD 方法层出不穷，但在复杂文本到 SQL 场景中的效果仍待验证。我们通过分析发现，现有 KD 方法在性能与效率的平衡上存在不足。为此，我们提出了 KID 方法，通过利用不完美数据，在不增加过多训练成本的情况下显著提升性能。KID 的核心在于模拟训练数据中的推理级联效应，从而有效解决训练与推理之间的不匹配问题。实验结果显示，KID 不仅在各类模型上实现了高达 +5.83% 的平均性能提升，还大幅提高了训练效率。
>
> https://arxiv.org/abs/2410.11371

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.11371](https://arxiv.org/abs/2410.11371)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)