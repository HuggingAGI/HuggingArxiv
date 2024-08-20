# FabricQA-Extractor：一款通过自然语言提问从文档中提取信息的问题解答系统

发布时间：2024年08月17日

`LLM应用` `数据管理` `信息提取`

> FabricQA-Extractor: A Question Answering System to Extract Information from Documents using Natural Language Questions

# 摘要

> 阅读理解模型在处理文本后，能以自然语言回答问题，为解决数据管理中的老难题——从非结构化文本中提取结构化数据——提供了新思路。尽管现有方法利用这些模型进行信息提取，但它们忽略了目标提取表的关系结构。为此，我们提出了一种名为“关系连贯性”的新模型，该模型通过利用关系结构知识来提升提取质量。我们将此模型整合到FabricQA-Extractor系统中，这是一个我们自主研发的端到端系统，旨在处理大规模文档提取任务。实验证明，在包含数百万段落的数据集上，关系连贯性显著提升了提取性能，并且FabricQA-Extractor在大规模数据集上的表现也得到了验证。

> Reading comprehension models answer questions posed in natural language when provided with a short passage of text. They present an opportunity to address a long-standing challenge in data management: the extraction of structured data from unstructured text. Consequently, several approaches are using these models to perform information extraction. However, these modern approaches leave an opportunity behind because they do not exploit the relational structure of the target extraction table. In this paper, we introduce a new model, Relation Coherence, that exploits knowledge of the relational structure to improve the extraction quality. We incorporate the Relation Coherence model as part of FabricQA-Extractor, an end-to-end system we built from scratch to conduct large scale extraction tasks over millions of documents. We demonstrate on two datasets with millions of passages that Relation Coherence boosts extraction performance and evaluate FabricQA-Extractor on large scale datasets.

[Arxiv](https://arxiv.org/abs/2408.09226)