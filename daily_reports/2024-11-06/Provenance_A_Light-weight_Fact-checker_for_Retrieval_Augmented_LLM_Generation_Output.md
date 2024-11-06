# 来源：用于检索增强型 LLM 生成输出的轻量级事实核查器
发布时间：2024年11月01日

`RAG`
> Provenance: A Light-weight Fact-checker for Retrieval Augmented LLM Generation Output
>
> 我们提出了一种用于检测检索增强生成（RAG）中非事实性输出的轻量级方法。给定一个上下文和假定的输出，我们计算一个事实性得分，该得分可以通过阈值来产生一个二元决策，以检查基于 LLM 的问答、摘要或其他系统的结果。与本身依赖于 LLM 的事实性检查器不同，我们使用紧凑的、开源的自然语言推理（NLI）模型，在运行时产生低延迟和低成本的可自由访问的解决方案，并且不需要 LLM 微调。该方法还通过将幻觉追溯到特定的上下文块，实现了对下游幻觉的缓解和纠正。我们的实验在广泛的相关开源数据集中显示出高的 ROC 曲线下面积（AUC），表明我们用于事实检查 RAG 输出的方法的有效性。
>
> https://arxiv.org/abs/2411.01022

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.01022](https://arxiv.org/abs/2411.01022)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)