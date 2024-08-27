# vitaLITy 2：借助大型语言模型，深入探索学术文献的奥秘

发布时间：2024年08月23日

`RAG` `学术研究` `开源软件`

> vitaLITy 2: Reviewing Academic Literature Using Large Language Models

# 摘要

> 传统的学术文献综述依赖于关键词搜索和相关引用的积累，但这种方法的精确度和准确性受限于关键词的选择，使得文献搜索如同大海捞针。为此，我们推出了vitaLITy 2，一个基于大型语言模型（LLM）的解决方案，能在文本嵌入空间中精准识别语义相关的文献。该系统包含了一个跨越1970至2023年的66,692篇论文的语料库，用户可通过三种语言模型生成的文本嵌入进行搜索。vitaLITy 2引入了创新的检索增强生成（RAG）架构，并支持通过增强提示的LLM进行交互，包括论文集的总结功能。此外，它提供了一个无需编程知识的聊天接口，让用户轻松执行复杂查询，并利用LLM从海量训练数据中提取的知识。我们通过两个实际应用场景展示了vitaLITy 2的实用性。该软件已作为开源项目在https://vitality-vis.github.io上发布。

> Academic literature reviews have traditionally relied on techniques such as keyword searches and accumulation of relevant back-references, using databases like Google Scholar or IEEEXplore. However, both the precision and accuracy of these search techniques is limited by the presence or absence of specific keywords, making literature review akin to searching for needles in a haystack. We present vitaLITy 2, a solution that uses a Large Language Model or LLM-based approach to identify semantically relevant literature in a textual embedding space. We include a corpus of 66,692 papers from 1970-2023 which are searchable through text embeddings created by three language models. vitaLITy 2 contributes a novel Retrieval Augmented Generation (RAG) architecture and can be interacted with through an LLM with augmented prompts, including summarization of a collection of papers. vitaLITy 2 also provides a chat interface that allow users to perform complex queries without learning any new programming language. This also enables users to take advantage of the knowledge captured in the LLM from its enormous training corpus. Finally, we demonstrate the applicability of vitaLITy 2 through two usage scenarios. vitaLITy 2 is available as open-source software at https://vitality-vis.github.io.

[Arxiv](https://arxiv.org/abs/2408.13450)