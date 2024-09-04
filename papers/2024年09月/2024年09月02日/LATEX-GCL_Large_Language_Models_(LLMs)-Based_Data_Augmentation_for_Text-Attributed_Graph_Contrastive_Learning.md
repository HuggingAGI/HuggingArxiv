# LATEX-GCL：利用 LLM 进行数据增强，应用于文本属性图的对比学习

发布时间：2024年09月02日

`LLM应用` `图学习`

> LATEX-GCL: Large Language Models (LLMs)-Based Data Augmentation for Text-Attributed Graph Contrastive Learning

# 摘要

> 图对比学习 (GCL) 作为一种自监督图学习方法，在多个领域备受瞩目。然而，针对文本属性图 (TAG) 的 GCL 研究尚属空白。传统增强技术如特征嵌入掩码无法直接应用于 TAG 的文本属性。简单地将 GCL 应用于 TAG 涉及通过语言模型将文本属性编码为嵌入，再输入 GCL 模块。此方法存在三大难题：信息损失、文本编码中的语义损失及隐式增强约束导致的不可控结果。为此，我们提出 LATEX-GCL 框架，借助大型语言模型 (LLM) 进行文本增强，并利用其强大的自然语言处理 (NLP) 能力克服上述难题，推动 GCL 在 TAG 任务中的应用。实验表明，LATEX-GCL 在四个高质量 TAG 数据集上表现卓越。相关源代码和数据集已公开，便于复现，访问链接：https://anonymous.4open.science/r/LATEX-GCL-0712。

> Graph Contrastive Learning (GCL) is a potent paradigm for self-supervised graph learning that has attracted attention across various application scenarios. However, GCL for learning on Text-Attributed Graphs (TAGs) has yet to be explored. Because conventional augmentation techniques like feature embedding masking cannot directly process textual attributes on TAGs. A naive strategy for applying GCL to TAGs is to encode the textual attributes into feature embeddings via a language model and then feed the embeddings into the following GCL module for processing. Such a strategy faces three key challenges: I) failure to avoid information loss, II) semantic loss during the text encoding phase, and III) implicit augmentation constraints that lead to uncontrollable and incomprehensible results. In this paper, we propose a novel GCL framework named LATEX-GCL to utilize Large Language Models (LLMs) to produce textual augmentations and LLMs' powerful natural language processing (NLP) abilities to address the three limitations aforementioned to pave the way for applying GCL to TAG tasks. Extensive experiments on four high-quality TAG datasets illustrate the superiority of the proposed LATEX-GCL method. The source codes and datasets are released to ease the reproducibility, which can be accessed via this link: https://anonymous.4open.science/r/LATEX-GCL-0712.

[Arxiv](https://arxiv.org/abs/2409.01145)