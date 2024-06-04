# AMGPT：专为增材制造领域设计的上下文查询大型语言模型

发布时间：2024年05月24日

`RAG

理由：这篇论文主要介绍了一个专为金属增材制造领域设计的LLM文本生成器“AMGPT”，并采用了检索增强生成（RAG）技术来动态地从专业文献中提取信息，以提高模型在该领域的应用性能。因此，这篇论文更符合RAG分类，因为它主要关注的是如何通过RAG技术增强特定领域的大型语言模型的应用效果。` `材料科学` `增材制造`

> AMGPT: a Large Language Model for Contextual Querying in Additive Manufacturing

# 摘要

> 通用大型语言模型（如GPT-4）在回答材料科学研究者的具体查询时可能显得力不从心，仅能提供一个大致框架，而无法深入到新型合金的制造细节和材料特性。相比之下，通过注入专业领域知识的小型模型可能更具优势，因为大型模型难以快速适应金属增材制造（AM）领域的快速研究进展。为此，我们开发了“AMGPT”，一个专为金属AM领域设计的LLM文本生成器，旨在帮助研究者和用户在AM文献的海洋中导航。我们采用了Hugging Face的预训练Llama2-7B模型，并结合检索增强生成（RAG）技术，动态地从约50篇AM论文和教科书的PDF文档中提取信息。通过Mathpix将这些文档转换为TeX格式，以便整合进由LlamaIndex管理的RAG流程。专家评估显示，RAG设置中的特定嵌入不仅加快了响应速度，还确保了生成文本的连贯性。

> Generalized large language models (LLMs) such as GPT-4 may not provide specific answers to queries formulated by materials science researchers. These models may produce a high-level outline but lack the capacity to return detailed instructions on manufacturing and material properties of novel alloys. Enhancing a smaller model with specialized domain knowledge may provide an advantage over large language models which cannot be retrained quickly enough to keep up with the rapid pace of research in metal additive manufacturing (AM). We introduce "AMGPT," a specialized LLM text generator designed for metal AM queries. The goal of AMGPT is to assist researchers and users in navigating the extensive corpus of literature in AM. Instead of training from scratch, we employ a pre-trained Llama2-7B model from Hugging Face in a Retrieval-Augmented Generation (RAG) setup, utilizing it to dynamically incorporate information from $\sim$50 AM papers and textbooks in PDF format. Mathpix is used to convert these PDF documents into TeX format, facilitating their integration into the RAG pipeline managed by LlamaIndex. Expert evaluations of this project highlight that specific embeddings from the RAG setup accelerate response times and maintain coherence in the generated text.

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/process_description3.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/hfe4.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/index_query6.png)

![AMGPT：专为增材制造领域设计的上下文查询大型语言模型](../../../paper_images/2406.00031/AMGPT.png)

[Arxiv](https://arxiv.org/abs/2406.00031)