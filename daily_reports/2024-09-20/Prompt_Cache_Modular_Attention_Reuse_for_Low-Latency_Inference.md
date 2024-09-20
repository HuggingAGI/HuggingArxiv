# 提示缓存：通过模块化注意力重用实现低延迟推理
发布时间：2023年11月07日


> Prompt Cache: Modular Attention Reuse for Low-Latency Inference
>
> 我们推出了 Prompt Cache，通过在不同提示间重用注意力状态，显著提升大型语言模型（LLM）的推理速度。许多提示包含重叠文本段，如系统消息、模板和上下文文档。我们的核心思路是，预先计算并存储这些常见文本段的注意力状态，以便在用户提示中快速重用。Prompt Cache 定义了可重用的“提示模块”，确保重用时的位置准确，并提供用户接口访问缓存状态。实验表明，Prompt Cache 大幅缩短了首次生成 token 的时间，尤其在长提示任务中，如文档问答和推荐。性能提升显著，从 GPU 推理的 8 倍到 CPU 推理的 60 倍，且不影响输出准确性，无需调整模型参数。
>
> https://arxiv.org/pdf/2311.04934

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/pdf/2311.04934](https://arxiv.org/pdf/2311.04934)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)