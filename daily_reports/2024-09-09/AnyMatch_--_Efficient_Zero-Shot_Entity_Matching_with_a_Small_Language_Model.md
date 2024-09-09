# AnyMatch -- 利用小型语言模型实现高效零-shot 实体匹配
发布时间：2024年09月06日


> AnyMatch -- Efficient Zero-Shot Entity Matching with a Small Language Model
>
> 实体匹配 (EM) 旨在确定两个记录是否指向同一现实实体，这在数据集成中至关重要，如产品目录或地址数据库。许多 EM 方法依赖标注示例，限制了其应用。我们专注于零-shot 实体匹配，即在没有标注示例的情况下进行匹配。尽管大型语言模型 (LLM) 在零-shot EM 中表现出色，但其低吞吐量和高成本限制了其应用。  我们通过 AnyMatch，一个在迁移学习中微调的小型语言模型，重新审视零-shot EM。我们提出多种创新数据选择技术，如通过 AutoML 过滤器选择难匹配对，生成额外属性级示例，以及控制标签不平衡。  在九个基准数据集上与十三个基线对比，AnyMatch 虽参数少，但预测质量优异：总体 F1 分数第二高，优于其他大型模型方法。此外，AnyMatch 成本优势显著：与使用 GPT-4 的 MatchGPT 相比，预测质量仅差 4.4%，但参数少四个数量级，推理成本降低 3,899 倍。
>
> https://arxiv.org/abs/2409.04073

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.04073](https://arxiv.org/abs/2409.04073)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)