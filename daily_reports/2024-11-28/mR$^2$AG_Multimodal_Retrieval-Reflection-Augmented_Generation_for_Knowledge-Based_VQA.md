# mR$^2$AG：针对基于知识的 VQA 的多模态检索-反思-增强式生成
发布时间：2024年11月22日

`多模态大模型`
> mR$^2$AG: Multimodal Retrieval-Reflection-Augmented Generation for Knowledge-Based VQA
>
> 先进的多模态大型语言模型（MLLMs）在 INFOSEEK 和 Encyclopedic-VQA 等基于知识的 VQA 任务中表现欠佳，这是因为其知识范畴有限且固定，往往致使回答含混不清、不够准确。于是，多模态检索增强生成（mRAG）顺势而生，为 MLLMs 提供全面且时新的知识，切实拓展了知识范畴。但当下的 mRAG 方法存在固有弊端，比如：1）即便无需外部知识，也会进行检索。2）缺少对支持查询的证据的判别。3）因额外的信息过滤模块或规则，增加了模型的复杂度。为克服这些缺陷，我们提出了一种新颖的通用框架，叫做	extbf{多模态	extbf{检索	extbf{-}	extbf{反思	extbf{-}	extbf{增强	extbf{生成}}（mR$^2$AG），它通过两个易于施行的反思操作达成自适应检索和有用信息定位，从而给出回答，同时避免了模型的高复杂度。在 mR$^2$AG 中，检索反思用于区分不同的用户查询，避免冗余的检索调用；相关性反思的引入是为了引导 MLLM 定位检索内容中的有益证据，并据此生成答案。另外，mR$^2$AG 能够融入任何训练有素的 MLLM 中，并在提出的 mR$^2$AG 指令调整数据集（mR$^2$AG-IT）上进行高效微调。mR$^2$AG 在 INFOSEEK 和 Encyclopedic-VQA 上的表现显著优于最先进的 MLLMs（如 GPT-4v/o）和基于 RAG 的 MLLMs，同时在众多视觉相关任务中保持了基础 MLLMs 的出色能力。
>
> https://arxiv.org/abs/2411.15041

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.15041](https://arxiv.org/abs/2411.15041)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)