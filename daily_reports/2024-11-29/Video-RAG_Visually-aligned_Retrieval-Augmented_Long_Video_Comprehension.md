# Video-RAG：视觉对齐的检索增强式长视频理解
发布时间：2024年11月20日

`RAG`
> Video-RAG: Visually-aligned Retrieval-Augmented Long Video Comprehension
>
> 现有的大型视频语言模型（LVLMs）因上下文受限，难以准确理解长视频。为化解此难题，对长上下文的 LVLMs 进行微调以及运用基于 GPT 的代理已成为颇具前景的解决之策。然而，微调 LVLMs 需大量优质数据和众多 GPU 资源，而基于 GPT 的代理则依赖专有模型（如 GPT-4o）。在本文中，我们提出了视频检索增强生成（Video-RAG），这是一种无需训练且经济高效的流程，它借助视觉对齐的辅助文本，助力促进跨模态对齐，同时提供超越视觉内容的额外信息。具体来说，我们利用开源的外部工具从纯视频数据（比如音频、光学字符和对象检测）中提取视觉对齐的信息，并以即插即用的方式将提取的信息作为辅助文本与视频帧和查询一道纳入现有的 LVLM 中。我们的 Video-RAG 有几大关键优势：（一）因单轮检索，计算开销小，轻巧便捷；（二）易于实现，与任何 LVLM 兼容；（三）在包括 Video-MME、MLVU 和 LongVideoBench 在内的长视频理解基准测试中，性能显著且持续提升。值得一提的是，当与 72B 模型配合使用时，我们的模型性能优于 Gemini-1.5-Pro 和 GPT-4o 等专有模型。
>
> https://arxiv.org/abs/2411.13093

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.13093](https://arxiv.org/abs/2411.13093)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)