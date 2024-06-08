# 微调预训练大型语言模型助力法律文件起草

发布时间：2024年06月06日

`LLM应用

理由：这篇论文主要探讨了如何利用未标注的法律文档微调大规模语言模型（LLM）以生成法律文件草案，并强调了信息隐私保护和信息安全的重要性。这属于LLM技术在特定领域（法律）的应用，因此归类为LLM应用。`

> Legal Documents Drafting with Fine-Tuned Pre-Trained Large Language Model

# 摘要

> 随着大规模语言模型（LLM）技术的进步，微调预训练模型已成为自然语言处理下游任务的常规手段。然而，法律领域的语言模型训练面临挑战，需要大量法律文档来教授模型法律术语及文档格式的特殊性。传统NLP方法依赖人工标注数据集，但在法律领域，这类数据集难以获取，限制了其在起草法律文件中的应用。本研究不仅展示了如何利用未标注的法律文档（无需中文分词）微调LLM，更关键的是，通过本地微调，我们能生成法律文件草案，同时加强信息隐私保护和提升信息安全。

> With the development of large-scale Language Models (LLM), fine-tuning pre-trained LLM has become a mainstream paradigm for solving downstream tasks of natural language processing. However, training a language model in the legal field requires a large number of legal documents so that the language model can learn legal terminology and the particularity of the format of legal documents. The typical NLP approaches usually rely on many manually annotated data sets for training. However, in the legal field application, it is difficult to obtain a large number of manually annotated data sets, which restricts the typical method applied to the task of drafting legal documents. The experimental results of this paper show that not only can we leverage a large number of annotation-free legal documents without Chinese word segmentation to fine-tune a large-scale language model, but more importantly, it can fine-tune a pre-trained LLM on the local computer to achieve the generating legal document drafts task, and at the same time achieve the protection of information privacy and to improve information security issues.

[Arxiv](https://arxiv.org/abs/2406.04202)