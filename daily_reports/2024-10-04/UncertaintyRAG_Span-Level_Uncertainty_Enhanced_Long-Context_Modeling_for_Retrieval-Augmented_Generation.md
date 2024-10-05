# UncertaintyRAG：通过跨度级不确定性增强，优化检索增强生成的长上下文建模
发布时间：2024年10月03日

`RAG`
> UncertaintyRAG: Span-Level Uncertainty Enhanced Long-Context Modeling for Retrieval-Augmented Generation
>
> 我们推出了 UncertaintyRAG，这是一种创新的长上下文 RAG 方法，通过基于 SNR 的跨度不确定性来估算文本块间的相似度。这种方法不仅提升了模型校准，还增强了鲁棒性，并减少了随机分块带来的语义偏差。基于此，我们设计了一种高效的无监督学习技术来训练检索模型，并采用了有效的数据采样与扩展策略。在 LLaMA-2-7B 上，UncertaintyRAG 以仅用 4% 训练数据的条件下，超越了基线 2.03%，达到了业界领先水平。通过跨度不确定性，我们的方法展现了卓越的校准能力，显著提升了长上下文 RAG 任务的泛化与鲁棒性。此外，UncertaintyRAG 提供了一个轻量级且无需微调的检索模型，可灵活集成到各种大型语言模型中，适应不同的上下文窗口长度。
>
> https://arxiv.org/abs/2410.02719

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.02719](https://arxiv.org/abs/2410.02719)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)