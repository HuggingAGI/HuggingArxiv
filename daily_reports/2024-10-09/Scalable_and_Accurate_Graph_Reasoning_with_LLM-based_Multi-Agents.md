# 利用 LLM 多代理系统实现高效且精准的图推理
发布时间：2024年10月07日

`知识图谱`
> Scalable and Accurate Graph Reasoning with LLM-based Multi-Agents
>
> 近期研究尝试利用大型语言模型 (LLM) 解决复杂图推理任务，但由于图结构复杂及 LLM 处理长文本的局限，现有方法在小型图和简单任务上准确性仍不尽人意。为此，我们推出 GraphAgent-Reasoner，一个无需微调的框架，通过多代理协作策略实现精确图推理。借鉴分布式图计算理论，我们将图问题分解为节点级小任务，分配给多个代理协同解决，大幅降低单个 LLM 处理的信息量和复杂性，提升推理准确性。只需增加代理数量，GraphAgent-Reasoner 便能高效扩展，适应包含上千节点的大型图。在 GraphInstruct 数据集上，该框架在多项式时间图推理任务中表现近乎完美，显著超越现有最佳模型，包括闭源和开源微调版本。此外，它还能处理网页重要性分析等实际图推理应用。
>
> https://arxiv.org/abs/2410.05130

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.05130](https://arxiv.org/abs/2410.05130)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)