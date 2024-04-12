# 在生物医学领域，LLMs的应用：探究临床命名实体识别的研究成果

发布时间：2024年04月10日

`LLM应用` `生物医学`

> LLMs in Biomedicine: A study on clinical Named Entity Recognition

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中表现出色，但在生物医学领域，由于医学术语的复杂性和数据的匮乏，它们面临挑战。本研究深入探讨了如何通过策略性地优化提示，提升LLMs在医学命名实体识别（NER）任务上的表现。研究发现，精心设计的生物医学提示至关重要，通过策略性地选择上下文示例，能显著提升性能，使得在临床NER的各个基准数据集中F1分数提升了15%至20%。同时，研究还表明，通过提示策略整合外部医学资源，能有效缩小通用型LLMs与专业医学NER需求之间的差异。我们借鉴检索增强生成（RAG）的方法，提出了一种新策略，能显著提升LLMs在零样本临床NER任务中的F1分数。相关代码将在论文发表后公开。

> Large Language Models (LLMs) demonstrate remarkable versatility in various NLP tasks but encounter distinct challenges in biomedicine due to medical language complexities and data scarcity. This paper investigates the application of LLMs in the medical domain by exploring strategies to enhance their performance for the Named-Entity Recognition (NER) task. Specifically, our study reveals the importance of meticulously designed prompts in biomedicine. Strategic selection of in-context examples yields a notable improvement, showcasing ~15-20\% increase in F1 score across all benchmark datasets for few-shot clinical NER. Additionally, our findings suggest that integrating external resources through prompting strategies can bridge the gap between general-purpose LLM proficiency and the specialized demands of medical NER. Leveraging a medical knowledge base, our proposed method inspired by Retrieval-Augmented Generation (RAG) can boost the F1 score of LLMs for zero-shot clinical NER. We will release the code upon publication.

[Arxiv](https://arxiv.org/abs/2404.07376)