# 大型语言模型（LLMs）自有所需：借助缺失信息导向框架，提升检索增强生成能力。

发布时间：2024年04月22日

`分类：RAG` `信息检索`

> LLMs Know What They Need: Leveraging a Missing Information Guided Framework to Empower Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过向大型语言模型（LLMs）注入最新相关信息，有效缓解了知识过时或产生幻觉的问题。尽管如此，RAG 在解析复杂的多步骤查询和检索相关文档时仍面临挑战，这需要 LLMs 逐步进行逻辑推理和信息检索。借鉴人类逐步搜寻所需信息的推理方式，我们自然而然地探索 LLMs 是否能够在每个推理环节中察觉到缺失的信息。本研究首先通过实验确认了 LLMs 在信息提取和识别信息空缺方面的能力。基于这一发现，我们提出了一种新颖的缺失信息引导检索-提取-解决框架（MIGRES），该框架通过识别缺失信息来生成定向查询，以指导后续的知识检索过程。此外，我们还设计了一种基于句子级别的重新排序过滤方法，用以从文档中排除不相关的内容，结合 LLMs 的信息抽取功能，从净化后的文档中抽取有用信息，进一步提升 RAG 的整体效能。在多个公共数据集上的广泛实验表明，MIGRES 方法具有显著优势，而深入的分析实验也验证了我们所提出模块的有效性。

> Retrieval-Augmented Generation (RAG) demonstrates great value in alleviating outdated knowledge or hallucination by supplying LLMs with updated and relevant knowledge. However, there are still several difficulties for RAG in understanding complex multi-hop query and retrieving relevant documents, which require LLMs to perform reasoning and retrieve step by step. Inspired by human's reasoning process in which they gradually search for the required information, it is natural to ask whether the LLMs could notice the missing information in each reasoning step. In this work, we first experimentally verified the ability of LLMs to extract information as well as to know the missing. Based on the above discovery, we propose a Missing Information Guided Retrieve-Extraction-Solving paradigm (MIGRES), where we leverage the identification of missing information to generate a targeted query that steers the subsequent knowledge retrieval. Besides, we design a sentence-level re-ranking filtering approach to filter the irrelevant content out from document, along with the information extraction capability of LLMs to extract useful information from cleaned-up documents, which in turn to bolster the overall efficacy of RAG. Extensive experiments conducted on multiple public datasets reveal the superiority of the proposed MIGRES method, and analytical experiments demonstrate the effectiveness of our proposed modules.

![大型语言模型（LLMs）自有所需：借助缺失信息导向框架，提升检索增强生成能力。](../../../paper_images/2404.14043/x1.png)

[Arxiv](https://arxiv.org/abs/2404.14043)