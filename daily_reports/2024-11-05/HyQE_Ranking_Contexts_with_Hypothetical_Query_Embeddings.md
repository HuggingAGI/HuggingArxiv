# HyQE：通过假设查询嵌入来排序上下文
发布时间：2024年10月19日


> HyQE: Ranking Contexts with Hypothetical Query Embeddings
>
> 在检索增强系统中，上下文排序技术常用于根据相关性对检索结果进行重新排序。传统方法通过嵌入空间中的相似性来衡量相关性，但往往不够准确。大型语言模型 (LLM) 也被用于排序，但在候选上下文增多时可能面临可扩展性问题，且需要特定领域数据的微调。我们提出了一种无需微调的排序框架，结合了嵌入相似性和 LLM 能力。该框架利用预训练 LLM 根据检索结果生成假设查询，并基于假设查询与用户查询的相似性进行排序。实验证明，我们的方法在多个基准测试中显著提升了排序效果。完整代码和数据已公开，详见 https://github.com/zwc662/hyqe。
>
> https://arxiv.org/abs/2410.15262

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.15262](https://arxiv.org/abs/2410.15262)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)