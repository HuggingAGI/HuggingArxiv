# AMGPT：专为增材制造领域设计的上下文查询大型语言模型

发布时间：2024年05月24日

`RAG

理由：这篇论文介绍了一个名为“AMGPT”的特定领域文本生成器，它是基于Hugging Face的预训练Llama2-7B模型，并在检索增强生成（RAG）框架下进行优化。论文中提到的关键技术包括动态整合专业文献信息和使用RAG流程，这些都是RAG技术的典型应用。因此，这篇论文应归类于RAG。` `材料科学` `增材制造`

> AMGPT: a Large Language Model for Contextual Querying in Additive Manufacturing

# 摘要

> 通用大型语言模型如GPT-4在回答材料科学研究者的具体查询时可能力不从心，仅能提供概述而无法给出新型合金制造和材料属性的详细指导。相比之下，通过整合专业领域知识的小型模型可能更具优势，因为大型模型难以快速适应金属增材制造领域的快速发展。为此，我们开发了“AMGPT”，一个专为金属增材制造查询定制的LLM文本生成器，旨在帮助研究者深入探索AM领域的丰富文献。我们采用Hugging Face的预训练Llama2-7B模型，在检索增强生成框架下，动态整合约50篇AM论文和教科书的信息。通过Mathpix将PDF文档转换为TeX格式，便于整合到LlamaIndex管理的RAG流程中。专家评估显示，RAG设置中的特定嵌入不仅加快了响应速度，还确保了生成文本的连贯性。

> Generalized large language models (LLMs) such as GPT-4 may not provide specific answers to queries formulated by materials science researchers. These models may produce a high-level outline but lack the capacity to return detailed instructions on manufacturing and material properties of novel alloys. Enhancing a smaller model with specialized domain knowledge may provide an advantage over large language models which cannot be retrained quickly enough to keep up with the rapid pace of research in metal additive manufacturing (AM). We introduce "AMGPT," a specialized LLM text generator designed for metal AM queries. The goal of AMGPT is to assist researchers and users in navigating the extensive corpus of literature in AM. Instead of training from scratch, we employ a pre-trained Llama2-7B model from Hugging Face in a Retrieval-Augmented Generation (RAG) setup, utilizing it to dynamically incorporate information from $\sim$50 AM papers and textbooks in PDF format. Mathpix is used to convert these PDF documents into TeX format, facilitating their integration into the RAG pipeline managed by LlamaIndex. Expert evaluations of this project highlight that specific embeddings from the RAG setup accelerate response times and maintain coherence in the generated text.

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/process_description3.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/hfe4.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/index_query6.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/AMGPT.png)

[Arxiv](https://arxiv.org/abs/2406.00031)