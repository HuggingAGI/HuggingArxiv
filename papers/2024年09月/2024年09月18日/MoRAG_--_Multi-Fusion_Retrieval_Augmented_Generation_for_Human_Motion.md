# MoRAG -- 多融合检索增强生成技术，专为人类运动设计

发布时间：2024年09月18日

`RAG` `人工智能`

> MoRAG -- Multi-Fusion Retrieval Augmented Generation for Human Motion

# 摘要

> 我们推出了 MoRAG，一种新颖的多部分融合检索增强生成策略，专为基于文本的人类动作生成设计。MoRAG 通过整合改进检索过程获取的额外知识，显著提升了动作扩散模型的性能。我们巧妙地利用大型语言模型 (LLM) 来纠正检索中的拼写错误和重述问题。采用多部分检索策略，MoRAG 在语言空间中展现了卓越的泛化能力。通过空间组合检索到的动作，我们生成了丰富多样的样本。更值得一提的是，利用低级别、特定部分的动作信息，MoRAG 还能为新文本描述构建动作样本。实验证明，MoRAG 框架可作为即插即用的增强模块，大幅提升动作扩散模型的表现。相关代码、预训练模型及示例视频即将在 https://motion-rag.github.io/ 发布。

> We introduce MoRAG, a novel multi-part fusion based retrieval-augmented generation strategy for text-based human motion generation. The method enhances motion diffusion models by leveraging additional knowledge obtained through an improved motion retrieval process. By effectively prompting large language models (LLMs), we address spelling errors and rephrasing issues in motion retrieval. Our approach utilizes a multi-part retrieval strategy to improve the generalizability of motion retrieval across the language space. We create diverse samples through the spatial composition of the retrieved motions. Furthermore, by utilizing low-level, part-specific motion information, we can construct motion samples for unseen text descriptions. Our experiments demonstrate that our framework can serve as a plug-and-play module, improving the performance of motion diffusion models. Code, pretrained models and sample videos will be made available at: https://motion-rag.github.io/

[Arxiv](https://arxiv.org/abs/2409.12140)