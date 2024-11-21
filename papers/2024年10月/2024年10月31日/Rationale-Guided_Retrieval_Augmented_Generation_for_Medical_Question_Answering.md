# 用于医疗问答的原理引导式检索增强生成

发布时间：2024年10月31日

`RAG` `生物医学` `医学问答`

> Rationale-Guided Retrieval Augmented Generation for Medical Question Answering

# 摘要

> 大型语言模型（LLM）在生物医学应用领域潜力巨大，然而却存在幻觉和知识陈旧的问题。尽管检索增强生成（RAG）常被用于应对这些难题，但它自身也面临一系列挑战：（1）LLM 易受无关或错误的上下文干扰，（2）医学查询往往难以精准获取有用信息，（3）检索器容易偏向其训练所用的特定源语料库。在此研究中，我们推出了 RAG$^2$（RAtionale-Guided RAG），这是一个能提升生物医学场景中 RAG 可靠性的新框架。RAG$^2$ 涵盖三项关键创新：基于困惑度标签的原理训练而成的小型过滤模型，能有选择地增强文档中的有用信息片段，同时滤除干扰项；将 LLM 生成的原理作为查询，以提升检索片段的效用；设计了一种能从四个综合的生物医学语料库中均匀检索片段的结构，有效降低了检索器的偏差。我们的实验表明，RAG$^2$ 使不同规模的先进 LLM 得以改进，提升幅度高达 6.1％，并且在三个医学问答基准测试中，其表现比之前最佳的医学 RAG 模型高出多达 5.6％。我们的代码可在 https://github.com/dmis-lab/RAG2 获取。

> Large language models (LLM) hold significant potential for applications in biomedicine, but they struggle with hallucinations and outdated knowledge. While retrieval-augmented generation (RAG) is generally employed to address these issues, it also has its own set of challenges: (1) LLMs are vulnerable to irrelevant or incorrect context, (2) medical queries are often not well-targeted for helpful information, and (3) retrievers are prone to bias toward the specific source corpus they were trained on. In this study, we present RAG$^2$ (RAtionale-Guided RAG), a new framework for enhancing the reliability of RAG in biomedical contexts. RAG$^2$ incorporates three key innovations: a small filtering model trained on perplexity-based labels of rationales, which selectively augments informative snippets of documents while filtering out distractors; LLM-generated rationales as queries to improve the utility of retrieved snippets; a structure designed to retrieve snippets evenly from a comprehensive set of four biomedical corpora, effectively mitigating retriever bias. Our experiments demonstrate that RAG$^2$ improves the state-of-the-art LLMs of varying sizes, with improvements of up to 6.1\%, and it outperforms the previous best medical RAG model by up to 5.6\% across three medical question-answering benchmarks. Our code is available at https://github.com/dmis-lab/RAG2.

[Arxiv](https://arxiv.org/abs/2411.00300)