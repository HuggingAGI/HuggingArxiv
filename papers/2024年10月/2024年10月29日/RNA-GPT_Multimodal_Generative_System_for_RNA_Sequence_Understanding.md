# RNA-GPT：用于 RNA 序列理解的多模态生成体系

发布时间：2024年10月29日

`LLM应用`

> RNA-GPT: Multimodal Generative System for RNA Sequence Understanding

# 摘要

> RNA 是携带生命关键遗传信息的重要分子，对药物研发和生物技术意义深远。然而，RNA 研究常因相关文献众多而受阻。为此，我们推出了 RNA-GPT 这一多模态 RNA 聊天模型，旨在借助丰富的 RNA 文献来简化 RNA 的发现。RNA-GPT 整合了 RNA 序列编码器、线性投影层和先进的大型语言模型（LLMs），以实现精准的表示对齐，能够处理用户上传的 RNA 序列并给出简洁准确的回应。基于可扩展的训练流程，RNA-GPT 运用 RNA-QA 这一自动系统，通过分治法结合 GPT-4o 和潜在狄利克雷分配（LDA）从 RNACentral 收集 RNA 注释，从而高效处理大型数据集并生成指令调优样本。我们的实验表明，RNA-GPT 能有效处理复杂的 RNA 问题，推动 RNA 研究。另外，我们还展示了 RNA-QA 这一包含 407,616 个 RNA 样本的数据集，用于模态对齐和指令调优，进一步增强了 RNA 研究工具的潜力。

> RNAs are essential molecules that carry genetic information vital for life, with profound implications for drug development and biotechnology. Despite this importance, RNA research is often hindered by the vast literature available on the topic. To streamline this process, we introduce RNA-GPT, a multi-modal RNA chat model designed to simplify RNA discovery by leveraging extensive RNA literature. RNA-GPT integrates RNA sequence encoders with linear projection layers and state-of-the-art large language models (LLMs) for precise representation alignment, enabling it to process user-uploaded RNA sequences and deliver concise, accurate responses. Built on a scalable training pipeline, RNA-GPT utilizes RNA-QA, an automated system that gathers RNA annotations from RNACentral using a divide-and-conquer approach with GPT-4o and latent Dirichlet allocation (LDA) to efficiently handle large datasets and generate instruction-tuning samples. Our experiments indicate that RNA-GPT effectively addresses complex RNA queries, thereby facilitating RNA research. Additionally, we present RNA-QA, a dataset of 407,616 RNA samples for modality alignment and instruction tuning, further advancing the potential of RNA research tools.

[Arxiv](https://arxiv.org/abs/2411.08900)