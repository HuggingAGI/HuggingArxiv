# LLaMA-Mesh：实现 3D 网格生成与语言模型的统一

发布时间：2024年11月14日

`LLM应用` `3D 生成` `语言模型`

> LLaMA-Mesh: Unifying 3D Mesh Generation with Language Models

# 摘要

> 此项工作致力于拓展在文本上预训练的大型语言模型（LLM）的能力，使其能在统一模型中生成 3D 网格。这具有关键优势：其一，借助 LLM 中已有的、源自像 3D 教程这类文本来源的空间知识；其二，达成对话式 3D 生成和网格理解。主要难题在于将 3D 网格数据有效标记为离散标记，以供 LLM 无缝处理。为此，我们推出 LLaMA-Mesh 这一创新方法，把 3D 网格的顶点坐标和面定义表述为纯文本，能与 LLM 直接融合且无需扩充词汇表。我们构建了有监督微调（SFT）数据集，让预训练的 LLM 能够：（1）依据文本提示生成 3D 网格；（2）按需生成交错的文本和 3D 网格输出；（3）理解并阐释 3D 网格。我们的工作率先表明，LLM 能够通过微调获取用于基于文本格式的 3D 网格生成的复杂空间知识，切实统一了 3D 和文本模态。LLaMA-Mesh 在维持强大文本生成性能的同时，实现了与从头训练的模型相当的网格生成质量。

> This work explores expanding the capabilities of large language models (LLMs) pretrained on text to generate 3D meshes within a unified model. This offers key advantages of (1) leveraging spatial knowledge already embedded in LLMs, derived from textual sources like 3D tutorials, and (2) enabling conversational 3D generation and mesh understanding. A primary challenge is effectively tokenizing 3D mesh data into discrete tokens that LLMs can process seamlessly. To address this, we introduce LLaMA-Mesh, a novel approach that represents the vertex coordinates and face definitions of 3D meshes as plain text, allowing direct integration with LLMs without expanding the vocabulary. We construct a supervised fine-tuning (SFT) dataset enabling pretrained LLMs to (1) generate 3D meshes from text prompts, (2) produce interleaved text and 3D mesh outputs as required, and (3) understand and interpret 3D meshes. Our work is the first to demonstrate that LLMs can be fine-tuned to acquire complex spatial knowledge for 3D mesh generation in a text-based format, effectively unifying the 3D and text modalities. LLaMA-Mesh achieves mesh generation quality on par with models trained from scratch while maintaining strong text generation performance.

[Arxiv](https://arxiv.org/abs/2411.09595)