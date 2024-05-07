# 全面召回：增强检索语言模型在长文档中提取长对象列表的应用

发布时间：2024年05月04日

`LLM应用` `文本分析` `信息检索`

> Recall Them All: Retrieval-Augmented Language Models for Long Object List Extraction from Long Documents

# 摘要

> 文本关系提取的方法通常追求高精准度，却牺牲了召回率。但要构建与特定主题相关联的长对象实体列表，高召回率不可或缺。在长篇文本中，相关对象的线索可能遍布多个段落，这增加了从长文本中抽取长列表的难度。我们介绍了L3X方法，它通过两个阶段来应对这一问题：首先，利用大型语言模型（LLM）进行召回导向的生成，并巧妙地增强检索技术；其次，进行精确度导向的审查，以确认或筛选候选项。我们的L3X方法在性能上显著超越了仅依赖LLM的生成方式。

> Methods for relation extraction from text mostly focus on high precision, at the cost of limited recall. High recall is crucial, though, to populate long lists of object entities that stand in a specific relation with a given subject. Cues for relevant objects can be spread across many passages in long texts. This poses the challenge of extracting long lists from long texts. We present the L3X method which tackles the problem in two stages: (1) recall-oriented generation using a large language model (LLM) with judicious techniques for retrieval augmentation, and (2) precision-oriented scrutinization to validate or prune candidates. Our L3X method outperforms LLM-only generations by a substantial margin.

![全面召回：增强检索语言模型在长文档中提取长对象列表的应用](../../../paper_images/2405.02732/intro.png)

![全面召回：增强检索语言模型在长文档中提取长对象列表的应用](../../../paper_images/2405.02732/x1.png)

![全面召回：增强检索语言模型在长文档中提取长对象列表的应用](../../../paper_images/2405.02732/x2.png)

[Arxiv](https://arxiv.org/abs/2405.02732)