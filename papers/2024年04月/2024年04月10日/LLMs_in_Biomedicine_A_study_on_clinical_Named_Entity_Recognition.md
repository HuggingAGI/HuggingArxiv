# 生物医学领域的大型语言模型：专注于临床命名实体识别的深入研究

发布时间：2024年04月10日

`LLM应用` `生物医学`

> LLMs in Biomedicine: A study on clinical Named Entity Recognition

# 摘要

> 大型语言模型（LLMs）在多样的自然语言处理（NLP）任务中展现了卓越能力，但在生物医学领域却因医学术语的复杂和数据的匮乏而面临挑战。本研究通过优化命名实体识别（NER）任务的策略，探讨了LLMs在医学领域的应用潜力。研究发现，精心设计的生物医学提示至关重要，策略性地挑选上下文实例能显著提升性能，使得临床NER的F1分数在所有基准数据集上平均提升了15-20%。此外，研究还指出，通过提示策略整合外部资源可以有效缩小通用型LLMs与专业医学NER需求之间的差异。我们提出的，受检索增强生成（RAG）启发的方法，能够显著提升LLMs在零次临床NER任务中的F1分数。相关代码将在论文发表后公开。

> Large Language Models (LLMs) demonstrate remarkable versatility in various NLP tasks but encounter distinct challenges in biomedicine due to medical language complexities and data scarcity. This paper investigates the application of LLMs in the medical domain by exploring strategies to enhance their performance for the Named-Entity Recognition (NER) task. Specifically, our study reveals the importance of meticulously designed prompts in biomedicine. Strategic selection of in-context examples yields a notable improvement, showcasing ~15-20\% increase in F1 score across all benchmark datasets for few-shot clinical NER. Additionally, our findings suggest that integrating external resources through prompting strategies can bridge the gap between general-purpose LLM proficiency and the specialized demands of medical NER. Leveraging a medical knowledge base, our proposed method inspired by Retrieval-Augmented Generation (RAG) can boost the F1 score of LLMs for zero-shot clinical NER. We will release the code upon publication.

[Arxiv](https://arxiv.org/abs/2404.07376)