# 利用大型语言模型优化关系数据库交互：探讨列描述如何提升文本到SQL的转换效率
发布时间：2024年08月08日

`代码编写`
> Improving Relational Database Interactions with Large Language Models: Column Descriptions and Their Impact on Text-to-SQL Performance
>
> 关系数据库常因表内容描述模糊不清而困扰，如含糊的列和难以理解的值，这不仅影响用户，也影响 Text-to-SQL 模型。本文利用大型语言模型 (LLM) 生成详尽的列描述，为关系数据库构建语义层。通过 BIRD-Bench 开发集，我们打造了 \textsc{ColSQL} 数据集，其中包含 LLM 与人工共同精炼的金标准列描述。评估显示，GPT-4o 和 Command R+ 在生成高质量描述方面表现卓越。我们还尝试用 LLM 作为评判来评估模型，尽管其结果与人类评估有差异，但此举旨在探索其潜力并寻求改进。为提升自动评估的可靠性，仍需更多研究。此外，详尽的列描述能显著提升 Text-to-SQL 的执行准确性，尤其是在列信息不明确时。本研究证实 LLM 是生成详细元数据、提升关系数据库可用性的有力工具。
>
> https://arxiv.org/abs/2408.04691

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04691/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04691/bar_plot_qualities_black.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04691/arbitrary_results_black.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04691/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.04691](https://arxiv.org/abs/2408.04691)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)